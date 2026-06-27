# Cognitive State

**Version:** 0.1

**Status:** Draft

**Last Updated:** 2026-06-27

---

## Purpose

The Cognitive State represents ALMA's complete internal understanding of a person at a specific moment in time.

It is the central working state shared across all cognitive components.

Rather than storing isolated information, the Cognitive State integrates observations, patterns, hypotheses, memory, confidence, and ongoing uncertainty into a single evolving representation.

---

## Fundamental Principle

Every conversation updates the Cognitive State.

Every cognitive component both reads from and contributes to the Cognitive State.

The Cognitive State continuously evolves as understanding improves.

---

## Core Components

The Cognitive State consists of multiple interconnected elements.

### Person Model

The current psychological representation of the individual.

---

### Memory

Long-term psychological knowledge accumulated across conversations.

---

### Active Observations

Recent structured observations awaiting further confirmation.

---

### Active Patterns

Recurring psychological regularities currently supported by evidence.

---

### Active Hypotheses

Current psychological explanations with associated confidence levels.

---

### Confidence State

The current confidence associated with observations, patterns, and hypotheses.

---

### Uncertainty State

Areas where understanding remains incomplete or ambiguous.

---

### Open Questions

Questions that may significantly improve understanding if explored.

---

### Recent Insights

Important reflections recently generated for the user.

---

## State Lifecycle

Conversation

↓

Interpretation

↓

Observation Update

↓

Pattern Update

↓

Hypothesis Update

↓

Memory Update

↓

Person Model Update

↓

Cognitive State Updated

---

## State Properties

The Cognitive State is:

* dynamic;
* evidence-based;
* explainable;
* probabilistic;
* continuously revisable.

It is never considered complete.

---

## Design Principles

The Cognitive State should:

* integrate all current psychological understanding;
* preserve uncertainty;
* remain internally consistent;
* support transparent reasoning;
* evolve incrementally.

No component should maintain an independent understanding outside the Cognitive State.

---

## Relationship to Components

The Cognitive State is shared by:

* Interpretation Engine
* Observation Model
* Pattern Model
* Hypothesis Engine
* Memory System
* Person Model
* Reflection Engine
* Question Engine

Each component reads the current state, performs its specialized function, and returns an updated state.

---

## Closing Principle

The Cognitive State is not a database.

It is ALMA's living cognitive representation of a person.

Every conversation refines it.

Every refinement improves understanding.
