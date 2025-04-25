# Term: bias

## v1.0.0

**Definition**  
A consistent deviation from neutral or expected output, perception, or behavior, originating from structural, procedural, or cognitive asymmetry within a defined system.

**Domain**: cognitive science, law, data systems, epistemology  
**Forms**: bias (noun), biased (adj), debiasing (verb), to bias (verb), biasing (adj participle)

**Depends on**:  
- system@1.0.0  
- input@1.0.0  
- output@1.0.0  
- asymmetry@1.0.0  
- expectation@1.0.0

---

### 🧬 Core Traits

- Must be **repeatable** and **predictable**  
- Must stem from **system design**, **data origin**, or **agent cognition**  
- Must be **scoped** — there is no global bias, only domain-specific bias

---

### 🎯 Scope Types

- `bias.systemic`: originates from system rules or defaults  
- `bias.algorithmic`: emerges from training data or architecture  
- `bias.cognitive`: from mental shortcuts or perceptual limits  
- `bias.procedural`: from order or framing in operations  
- `bias.confirmation`: favoring prior beliefs over new data  

---

### 🚫 Exclusions

- **Disagreement** ≠ bias  
- **Unpopular output** ≠ bias  
- **Bias** is not a value judgment in this definition — it is a *detectable pattern*

---

### ⚠️ Sideloading Risk

Extreme.  
The term is commonly used as an **ideological bludgeon** or to **discredit** without analysis.

Invalid examples:
- “That study is biased” → requires scoped mechanism (`bias.data.origin@`)  
- “He’s biased” → must be shown through pattern, not belief  
- “Bias against the majority” → contradiction unless scoped as `bias.structural.privilege@`

---

### 🔧 Usage in Systems

To label a system as biased:
- Declare **expected output baseline**  
- Show **consistent deviation**  
- Trace to structural or cognitive **asymmetry**  
- Prove **system awareness** or **design source**

---

### 🔐 Governance Notes

- Bias is **not a moral failure** — it is a semantic and statistical condition  
- Moral claims must be layered on top of bias via `harm`, `intent`, or `violation`  
- Systems may be biased *without malice*, but not without impact

**Status**: locked  
**Version**: 1.0.0  
**Locked by**: SIG/Semio
