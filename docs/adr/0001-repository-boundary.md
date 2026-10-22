<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
AER-LINK-WITNESS — repository foundation
-->

# Decision: independently observe source-owned event links

## Context

Spike-bit sources, packet routers, priority queues and delay taps have different event and acceptance semantics. Counting every input pulse or every output as the same population can hide coalescing, fanout, duplicates, censored work and capture gaps.

## Decision

AER Link Witness owns instrument generator and monitor IP, prior complete schedules, independent sequence and pending-work analysis, and reports. SC-NeuroCore retains the actual DUT implementations. Loop Timing Witness supplies admitted capture and timebase; installed Evidence Manifest Toolkit supplies shared evidence operations. Separate consumers preserve exact tested scope. Studio renders existing results.

## Consequences

Repository tooling can be qualified before an instrument exists. Source identity, independent simulation and physical qualification remain separate. Full expected and observed populations, payload/time/coverage and complete pending windows are required. A finite sweep, signed bytes or received-only maximum cannot establish a universal link guarantee.
