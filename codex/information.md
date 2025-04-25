# Term: information

## v1.0.0

**Definition**  
**Information** is structured or organized data that carries meaning, enabling communication, orientation, or action. It exists as a bridge between raw signals (data) and understanding (knowledge). Information becomes useful when it is interpretable by an agent (human or machine) and situated in a context. It is objective in form but always relative in interpretation.

**Domain**: communication, computing, epistemology, law, language  
**Forms**: information (noun), inform (verb), informative (adj), informed (adj)

**Depends on**:  
- **data@1.0.0**  
- **signal@1.0.0**  
- **context@1.0.0**  
- **meaning@1.0.0**  
- **agent@1.0.0**

---

### 🔍 Core Characteristics

- **Structured Data**: Information organizes raw inputs (data) into **patterns**, **formats**, or **statements** that can be perceived and used.

- **Carrier of Meaning**: It becomes **information** only when it is **interpretable**—it must carry meaning to a recipient, whether through language, code, signal, or symbol.

- **Contextual Relevance**: What counts as information depends on the situation and the receiver’s frame of reference. A pattern is only informative if it changes or clarifies the state of knowledge for someone.

- **Medium-Agnostic**: Information can be encoded in language, numbers, visual symbols, sound, or DNA—it is not tied to a specific form.

- **Low-Level Truth Dependency**: Information can be **false or misleading**, and still be information. This distinguishes it from **knowledge**, which requires truth or justification.

---

### 🚧 Exclusions

- **Random Data**: Noise or unstructured data is not information unless a recipient assigns interpretable meaning to it.

- **Truthfulness**: Something can be **false** or **deceptive** and still qualify as information if it affects belief, choice, or response.

- **Subjective Impressions**: Emotions, intuitions, or raw experience aren’t information unless encoded and shared in a form that others can interpret.

---

### 💣 Sideloading Risk

Moderate.  
- **Sideloading** occurs when **information** is treated as **knowledge** without validation, or when bias is embedded in data structures and labeled as "neutral information."

Invalid examples:
- “We are just giving the public information.” → But if that information is selected or framed to manipulate, it carries **bias**, not neutrality.
- “The algorithm gives objective information.” → Algorithms structure data, but always according to parameters, goals, and training inputs.

---

### 🔁 Variants

- `information.raw`: Minimal transformation of data—such as logs, signals, metrics. Only slightly structured but already has potential interpretability.

- `information.encoded`: Stored in specific symbolic formats—binary, textual, visual—that require decoding to interpret.

- `information.semantic`: Information explicitly tied to meaning in a given system (e.g., a sentence in a language, or an entry in Logotecture).

- `information.misleading`: Intentionally or unintentionally incorrect or distorted information that affects judgment or belief.

- `information.ambient`: Passively present, not directly delivered but available for interpretation (e.g., visual cues, background noise with significance).

---

### 🔐 Governance Notes

- **Information Integrity**: Systems must ensure information has traceability, coherence, and auditability, especially when used in decision-making.

- **Right to Information**: In governance, transparency means **timely, accessible, accurate** information that can be used to exercise rights or hold actors accountable.

- **Information ≠ Intelligence**: Intelligence systems process and prioritize information, but raw data alone does not become intelligence without context and intent.

- **AI Context**: For artificial agents, **information** is the substrate from which meaning is parsed, actions are selected, and states are updated. Its quality governs trustworthiness.
