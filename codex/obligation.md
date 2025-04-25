# Term: obligation

## v1.0.0

**Definition**  
A binding requirement or duty assigned to an agent within a defined system, arising from a contract, social expectation, or legal framework, which demands action, inaction, or specific behavior under specified conditions.

**Domain**: legal, ethical, contractual, procedural  
**Forms**: obligation (noun), obligated (adj), to obligate (verb), obligatory (adj)

**Depends on**:  
- agent@1.0.0  
- responsibility@1.0.0  
- capacity@1.0.0  
- system@1.0.0  
- enforceability@1.0.0  

---

### 🔍 Key Components

- **Traceability**: must be linked to a specific **agent** and **action/inaction**  
- **Enforceability**: there must be a defined consequence or enforcement mechanism  
- **Scoped**: applies only within a bounded **system** and **time frame**  
- **Legitimacy**: arises from a recognized or agreed-upon framework (law, contract, social contract)

---

### 🚧 Exclusions

- **Moral or abstract obligations** without **actionable consequences** or **definition**  
- **Obligations without enforcement** (e.g. voluntary charity work) unless formalized

---

### 💣 Sideloading Risk

Moderate — obligations are commonly **blurred** into moral or symbolic categories, or inflated rhetorically.

Invalid examples:
- “You have an obligation to be a good citizen” → requires scoped system of accountability  
- “The company has an obligation to fix this” → must show explicit contract or policy  
- “We have a moral obligation” → must be codified within system to be actionable

---

### 🔁 Variants

- `obligation.contractual`: a legally defined and enforceable duty within a contract  
- `obligation.legal`: an enforceable duty arising from law or statutory requirement  
- `obligation.ethical`: moral duties codified into enforceable frameworks (e.g. professional conduct rules)  
- `obligation.social`: socially accepted duties, but with defined consequences (e.g. "pay your taxes")

---

### 🔐 Governance Notes

- Obligations must **not be assumed** — they must be **explicitly defined** and **actionable**
- A **contractual obligation** cannot exist unless the **contract** can be audited and enforced  
- **Obligation updates** must be **transparent** to all agents involved  

**Status**: locked  
**Version**: 1.0.0  
**Locked by**: SIG/Semio
