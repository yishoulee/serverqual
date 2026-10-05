# Research Method and Limitations

ServerQual was an early exploratory business investigation. The method produced useful domain understanding, but it should **not** be presented as a strong validation design.

## What was done

### 1. Desk research

The project reviewed official and ecosystem material on:

- server platforms
- operating-system support
- certification programs
- firmware and drivers
- qualification and validation workflows
- support boundaries

A historical project record states that more than 70 official technical pages were screened. This repository does not independently re-audit that count.

### 2. Workflow mapping

Qualification work was decomposed into recurring activities such as:

- configuration capture
- compatibility and support research
- test planning
- regression testing
- evidence collection
- defect reproduction
- vendor escalation
- retesting
- release/change decisions

This helped establish that the technical activity exists.

It did **not** establish that an independent external provider could sell a stand-alone service around it.

### 3. Field observations

Industry-event conversations and observations in Taiwan were used to see where OS/platform qualification appeared relevant and where the original framing did not fit.

These observations were directional. They were not a qualified buyer sample and should not be counted as customer validation.

### 4. One dedicated practitioner consultation

One dedicated external practitioner consultation was completed.

The consultation was useful because it exposed practical issues around:

- procurement constraints
- unclear hardware revisions/documentation
- Linux support
- component replacement
- local supplier trust
- warranty / recourse

But one consultation cannot establish:

- market size
- common willingness to pay
- Europe-wide procurement behavior
- repeat purchase
- a viable sales motion
- acceptance of ServerQual's proposed artifact

## Methodological weaknesses

### Too many hypotheses

The project expanded to 20 hypotheses before proving the common core assumption.

That was too broad for the available discovery capacity.

### No fixed first buyer

The investigation moved across enterprise teams, OEM/ODM, integrators, component vendors, legacy users, and other segments.

A stronger design would have fixed one segment and one buyer role first.

### Buyer chain was mapped but not verified

The project reasoned about:

- user
- technical authority
- sponsor
- economic buyer
- purchasing/security

But these roles were not verified together in a real account.

### Behavioral thresholds were not defined early enough

A stronger experiment would have specified in advance what buyer behavior would count as evidence, for example:

- sharing a live change artifact
- introducing the budget owner
- accepting a scoped proposal
- paying for a pilot
- agreeing that the output would change a real approval decision

Without a threshold and a deadline, research can continue without actually testing the purchase hypothesis.

### Solution design came too early

The project designed:

- evidence packs
- qualification dossiers
- service workflows
- pricing ranges
- capacity models
- cash-flow scenarios

before demonstrating that a buyer wanted the output.

These were useful feasibility exercises, but they were not demand evidence.

### Resource feasibility was underweighted

Some later hypotheses required combinations of:

- multi-platform hardware access
- security permissions
- specialist engineering depth
- vendor/customer trust
- low-latency response
- capital

Those requirements should have disqualified or deprioritized several hypotheses earlier.

## What would have been a better method

The next version of this type of investigation should use a much narrower test:

1. **One buyer** — one role in one segment
2. **One live trigger** — release, BOM change, support failure, deadline, or maintenance event
3. **One decision** — what will the buyer approve, delay, buy, ship, escalate, or deploy?
4. **One bounded deliverable**
5. **One behavioral / price test**
6. **One time-boxed stop rule**

The goal should be to test the riskiest purchase assumption before building a broad market map or financial model.

## Evidence boundary

This project did not produce commercial validation.

Its evidence is best read as:

**technical plausibility + limited external discovery + structural warning signals + a justified no-go.**
