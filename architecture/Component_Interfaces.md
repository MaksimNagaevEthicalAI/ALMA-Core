# Component Interfaces

**Version:** 0.1

**Status:** Draft

**Last Updated:** 2026-06-27

---

## Purpose

The Component Interfaces document defines how ALMA's core cognitive components exchange information.

Each component has a clearly defined responsibility.

Components communicate through structured outputs rather than direct access to each other's internal logic.

This separation preserves modularity, transparency, and future extensibility.

---

## Design Principles

* Every component has a single responsibility.
* Every component has defined inputs and outputs.
* Components exchange structured cognitive objects.
* Components remain independent of implementation details.
* Components should be replaceable without redesigning the entire architecture.

---

## Core Interfaces

### Conversation → Interpretation Engine

Input:

* Raw conversation
* Conversation metadata

Output:

* Candidate interpretations

---

### Interpretation Engine → Observation Model

Input:

* Candidate interpretations

Output:

* Structured observations

---

### Observation Model → Pattern Model

Input:

* Observations

Output:

* Candidate patterns

---

### Pattern Model → Hypothesis Engine

Input:

* Confirmed patterns

Output:

* Active hypotheses

---

### Hypothesis Engine → Memory System

Input:

* Validated hypotheses
* Confidence updates

Output:

* Updated psychological memory

---

### Memory System → Person Model

Input:

* Long-term psychological knowledge

Output:

* Updated person representation

---

### Person Model → Reflection Engine

Input:

* Current psychological model

Output:

* Reflections
* Insights

---

### Reflection Engine → Question Engine

Input:

* Current reflections
* Remaining uncertainty

Output:

* Next question

---

### Question Engine → Conversation

Input:

* Selected question

Output:

* Next conversational interaction

---

## Closing Principle

No component should bypass another component.

Psychological understanding emerges through the complete cognitive pipeline rather than isolated reasoning steps.
