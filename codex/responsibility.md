# Term: responsibility

## v1.0.0

**Definition**  
A traceable binding between an agent and a defined obligation, enforceable within a system when conditions for action, capacity, and scope are met.

**Domain**: legal, ethical, procedural, systemic  
**Forms**: responsibility (noun), responsible (adj), to bear responsibility (verb phrase), irresponsibility (negated)

**Depends on**:  
- agent@1.0.0  
- obligation@1.0.0  
- scope@1.0.0  
- capacity@1.0.0  
- enforceability@1.0.0  

---

### 🔍 Key Characteristics

- **Traceable**: must link to a specific agent and origin point  
- **Scoped**: applies only within bounded domains and declared conditions  
- **Activatable**: not a moral abstract — must trigger action, inaction, or redress  
- **Enforceable**: has consequence pathways when not fulfilled

---

### ✋ Exclusions

- **Rhetorical responsibility** (e.g. “society is responsible”) must be scoped under `collective.responsibility@`  
- **Inherited blame** or **guilt metaphors** (e.g. “you benefit, so you’re responsible”) are not valid unless structurally defined

---

### 💣 Sideloading Risk

Very high — often used symbolically, evasively, or emotionally.

Examples of invalid uses:
- “We all share some responsibility” → ambiguous → invalid  
- “No one knew who was responsible” → system failure if traceability is lost  
- “He’s responsible because he *could have known*” → requires `foreseeability@`

---

### 🔁 Variant Notes

- `shared.responsibility`: multiple agents tied to the same obligation; requires distribution method  
- `proxy.responsibility`: agent holds duty on behalf of another; must be declared and consented

---

### 🔐 Governance Notes

- Responsibility is **not** voluntary  
- It is triggered by structural links — **roles, contracts, assignments, roles, capacity**  
- Declining responsibility must also be **auditable** and **registered**

**Status**: locked  
**Version**: 1.0.0  
**Locked by**: SIG/Semio
