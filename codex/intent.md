# Term: intent

## v1.0.0

**Definition**  
A condition in which an agent initiates or supports an action or state-change with foreknowledge of its likely outcome, based on available information and within the limits of their modeled cognition.

**Domain**: legal, logic, cognitive modeling  
**Forms**: intent (noun), intentional (adj), intentionally (adv), to intend (verb)

**Depends on**:  
- agent@1.0.0  
- action@1.0.0  
- outcome@1.0.0  
- cognition@1.0.0  
- probability@1.0.0

**Justification**  
`Intent` is pivotal in assessing moral and legal responsibility. It must be tied to **information available**, **likelihood of outcome**, and **agency capacity** — not inferred solely from consequence.

**Core Criteria**  
- Action must originate from agental decision or support  
- Outcome must be **predictable** above a defined probability threshold  
- Agent must have **cognitive access** to that prediction  
- Passive allowance with such knowledge qualifies as intent

**Variants**  
- `intent.reckless`: intent through disregard of high-likelihood harm  
- `intent.willful`: intent with direct goal alignment  
- `intent.neglectful`: intent by failure to act within role-defined duty

**Sideloading Risk**:  
Very high — `intent` is often falsely projected (e.g. "they *intended* to oppress") or falsely denied ("no way to know what they meant").  
This definition forces **operationalization** via info access + action traceability.

**Exclusions**  
- Emotional assumptions (e.g. "they looked angry") are not sufficient  
- Legal fictions such as “corporate intent” require explicit scoping: `intent.corporate@1.0.0`

**Governance Notes**  
Intent must always be **linked to evidence graph** in legal AI systems.  
In the absence of full knowledge, fallback to **`foreseeability`** or **`recklessness`** applies.

**Status**: locked  
**Version**: 1.0.0  
**Locked by**: SIG/Semio
