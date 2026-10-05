# Service Framing History

This file records how the ServerQual service idea changed during the investigation.

It should **not** be read as a sequence of validated product iterations. The project did not have enough external evidence to support that interpretation.

The more accurate reading is that the project kept reframing the same broad technical domain while the core purchase assumption remained unresolved.

## Core purchase assumption

Most versions depended on some form of this claim:

> A customer will trust an independent new provider to produce qualification evidence or analysis, will allow that output to affect a real procurement / release / support / change decision, and will pay separately for it.

That assumption was never established.

## Framing A — Broad "Qualification as a Service"

A broad external service for validating combinations of:

- server hardware
- firmware
- drivers
- operating systems
- virtualization
- components

### Why it was weak

The scope was too broad.

It also competed directly or indirectly with:

- OEM qualification teams
- internal validation organizations
- OS/vendor certification programs
- system integrators
- established laboratories

**Candid result:** poor starting frame. It began with a technical category rather than one buyer and one purchase event.

---

## Framing B — Independent qualification evidence

A narrower idea was to produce a reproducible evidence package for one exact platform configuration or change.

Possible cases included:

- firmware upgrades
- OS upgrades
- driver changes
- NIC/storage substitutions
- virtualization changes
- accelerator integration

### Why it looked better

The artifact was more bounded and easier to describe.

### Why it was still weak

The project moved from:

**"a bounded evidence pack can be produced"**

to:

**"a customer will buy and accept that pack"**

without proving the second statement.

The idea therefore remained a **solution hypothesis**, not a validated customer problem.

**Candid result:** technically coherent, purchase assumption unproven.

---

## Framing C — Certification readiness

Another idea was to support vendors before official certification by helping execute test plans, collect evidence, and close defects.

### Why it looked plausible

There can be deadlines, workload spikes, and evidence requirements before certification.

### Why it remained weak

The hypothesis required several assumptions to be true simultaneously:

- the vendor outsources sensitive pre-certification work
- an external newcomer receives system access
- the external work is trusted
- the work is not already handled by internal teams, partners, or established labs
- a budget exists for this separate engagement

These assumptions were not validated.

**Candid result:** plausible niche on paper, weakly evidenced.

---

## Framing D — Server change readiness

The later framing moved closer to an operational decision:

> **Know whether a server change is safe before the maintenance window.**

A proposed workflow included:

1. capture the current environment
2. define the proposed change
3. research supportability and compatibility
4. identify affected systems
5. identify blockers and prerequisites
6. define test/canary scope
7. define rollback considerations
8. produce a recommendation

### Why this was an improvement

It moved from selling "evidence" toward a concrete decision event.

### Why it still did not justify continuation

The project still lacked:

- a fixed buyer
- a verified budget owner
- customer acceptance of the deliverable
- proof that the work would be purchased separately
- a differentiated channel position
- a paid pilot

**Candid result:** a better framing, but still not a validated business.

---

## The 20-hypothesis problem

The broader project register eventually contained 20 ideas spanning:

- exact-stack changes
- certification readiness
- component substitution
- evidence packaging
- incident reproduction
- monitoring
- emergency firmware/security work
- virtualization/HCI upgrades
- air-gapped environments
- legacy support
- procurement acceptance
- workload performance
- AI systems
- Redfish/BMC regression
- cross-OEM testing
- OS-release readiness
- remote/edge systems
- shared laboratory infrastructure
- BIOS/power/thermal/NUMA tuning
- compatibility intelligence

These were not one coherent market.

Some were customer jobs, some were artifacts, some were specialist engineering businesses, some were software/data products, and one was a capital model.

See [Hypothesis Quality Audit](hypothesis-quality-audit.md) for the individual ratings.

## Final interpretation

The project did not fail because it selected one excellent hypothesis and discovered the market rejected it.

It failed earlier than that:

**the hypothesis portfolio itself was too broad, mixed, and under-specified to support efficient validation.**

The eventual no-go was still the correct decision.
