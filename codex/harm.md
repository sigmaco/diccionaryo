# Term: harm

## v1.0.0

**Definition**  
A measurable alteration to the state of an agent, system, or object resulting in degradation of function, loss of capacity, or reduction in integrity, occurring without prior justified consent.

**Domain**: legal, medical, computational, ethical  
**Forms**: harm (noun), to harm (verb), harmful (adj), harmed (past), harmless (negated)

**Depends on**:  
- agent@1.0.0  
- system@1.0.0  
- integrity@1.0.0  
- consent@1.0.0  

**Justification**  
The definition of `harm` must be machine-resolvable and human-auditable. It cannot rely on cultural intuition. This framing makes `harm` actionable in law, health systems, and AI regulation.

**Criteria for Harm**  
- Alteration must be *measurable*  
- Effect must be *degradative* or *limiting*  
- Subject must not have *pre-consented* within scope of known risk  
- Must be verifiable in state delta

**Sideloading Risk**:  
High — term is often inflated for rhetorical effect or selectively denied in legal framing.  
Metaphoric uses (e.g. "harm to image", "harm to democracy") require scoping:  
→ `harm.reputational@1.0.0`, `harm.institutional@1.0.0`, etc.

**Examples**  
- Physical harm: fractured bone from battery  
- Digital harm: corruption of stored data  
- Psychological harm: diagnosed trauma with functional loss  
- Legal harm: unauthorized denial of lawful capacity (e.g. right to testify)

**Exclusions**  
- Emotional discomfort *without functional degradation* is not classified as `harm` in this scope  
- Social/political offense is not automatically `harm` unless criteria are met

**Governance Notes**  
This definition prioritizes **objective conditions over felt claims**. Subjective experience may inform **evidence**, not the baseline criteria.

**Status**: locked  
**Version**: 1.0.0  
**Locked by**: SIG/Semio
