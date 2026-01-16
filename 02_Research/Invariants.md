# Continuity Engine 2.1 — Invariants

## 1. Purpose of this document
This document defines the **invariants** of CE 2.1 — the structural rules that must remain true for the system to function.  
Invariants protect CE 2.1 from drift, corruption, misinterpretation, and accidental redesign.

These are the “laws of motion” for the Continuity Engine.

---

## 2. What an invariant is
An invariant is a rule that must hold across:

- all domains  
- all modes  
- all stewards  
- all versions  
- all contexts  

If an invariant breaks, CE 2.1 stops being CE 2.1.

---

## 3. Core Invariants

### 3.1 Continuity First  
All operations must preserve continuity across:
- time  
- identity  
- decisions  
- domains  

No subsystem may violate continuity to achieve a local gain.

---

### 3.2 Structure Over Content  
CE 2.1 operates on **structure**, not subject matter.  
Domains differ in content, but share structural patterns.  
The system must always extract structure before interpreting content.

---

### 3.3 Domain Rotation Prevents Blindness  
No insight is complete until tested across multiple domains.  
Single‑domain reasoning is treated as incomplete by definition.

---

### 3.4 Questions Drive Discovery  
The Question Engine is the primary driver of insight.  
If questions stagnate, the system stagnates.

---

### 3.5 Truth Must Be Cross‑Domain  
A “truth” is only accepted if it:
- survives domain rotation  
- survives mode shifts  
- survives steward variation  
- survives time  

If it collapses under rotation, it is not a CE‑valid truth.

---

### 3.6 Steward-as-Instrument  
The steward’s internal state (mode, identity, resonance) is part of the system.  
Ignoring the steward breaks the architecture.

---

### 3.7 Recursion Is Mandatory  
CE 2.1 must be able to:
- operate on itself  
- refine its own protocols  
- update its own architecture  

A non‑recursive CE is a dead CE.

---

### 3.8 Transmission Integrity  
Any change to CE must:
- preserve invariants  
- preserve identity  
- preserve continuity across versions  

If a proposed change violates an invariant, it is rejected.

---

## 4. Invariant Violations
A violation occurs when:
- continuity is broken  
- structure is ignored  
- domain rotation is skipped  
- the steward’s mode is misaligned  
- recursion is blocked  
- truths are accepted without cross‑domain testing  

Violations trigger recovery patterns described in `Recovery-Patterns.md`.

---

## 5. Relationship to other documents
- `Foundations.md` explains why these invariants exist.  
- `Architecture.md` shows where each invariant lives in the system.  
- `Methods.md` describes how these invariants were derived and validated.

---

## 6. Status
- Version: 0.1 (Invariant scaffold)
- Steward: Richard Allen Schram Jr (Pappy)
- Notes: Additional invariants may be added only if they meet the criteria above.
