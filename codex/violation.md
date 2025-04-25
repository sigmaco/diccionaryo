# Term: violation

## v1.0.0

**Definition**  
The provable failure to fulfill a bound obligation, under conditions where the agent held capacity, the responsibility was scoped, and the enforcement system was active.

**Domain**: legal, procedural, contractual, systemic  
**Forms**: violation (noun), to violate (verb), violator (agent-noun), violated (adj/past)

**Depends on**:  
- responsibility@1.0.0  
- obligation@1.0.0  
- enforceability@1.0.0  
- scope@1.0.0  
- capacity@1.0.0  

---

### 🔍 Core Conditions

- The agent was **bound** to the obligation  
- The agent had **capacity** to act or abstain  
- The **scope** of obligation was active at time of breach  
- The system allows for **verification and enforcement**  

---

### 🚧 Exclusions

- **Moral claims** (e.g. “a violation of decency”) not bound to a system are out of scope  
- **Technical error** without active responsibility is not a violation  
- **Retroactive reinterpretation** of rules does not generate a violation unless obligation versioning supports retroactivity

---

### 💣 Sideloading Risk

High — often inflated rhetorically or denied via vagueness.

Invalid uses:
- “They violated the spirit of the law” → requires `law.spirit@` to be scoped  
- “This is a violation of our values” → requires `value.system@` with declared enforcement  
- “They didn’t know” → if capacity and foreseeability were present, still a violation

---

### 🔁 Variants

- `violation.technical`: breach due to system-process error  
- `violation.legal`: violation within formal legal structure  
- `violation.contractual`: as defined by versioned contract  
- `violation.silent`: unreported or unacknowledged, but still fulfillable by the framework

---

### 🔐 Governance Notes

- All violations must be **logically resolvable**, **verifiable**, and **scope-bound**  
- Perpetual or unscoped obligations cannot generate valid violations  
- Responsibility must be matched to scope at time of action

**Status**: locked  
**Version**: 1.0.0  
**Locked by**: SIG/Semio
