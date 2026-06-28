# Component Interfaces

Version: 0.2

Status: Draft

Last Updated: 2026-06-28

---

# Purpose

The Component Interfaces document defines how ALMA's cognitive components communicate while maintaining a unified Cognitive State.

Components do not communicate through internal implementation details.

Each component receives the current Cognitive State, performs its specialized reasoning, and returns an updated Cognitive State.

This architecture guarantees modularity, transparency, and extensibility.

---

# Fundamental Principle

Every component has a single responsibility.

Every component reads the current Cognitive State.

Every component contributes only its own refinement.

No component owns the complete understanding of a person.

The Cognitive State is the only shared cognitive representation.

---

# General Processing Interface

Every cognitive component follows the same interface.

Input:

- Current Cognitive State
- Conversation data (when available)

↓

Component Processing

↓

Output:

- Updated Cognitive State

Components never modify another component directly.

---

# Core Component Flow

Conversation

↓

Interpretation Engine

↓

Observation Model

↓

Pattern Model

↓

Hypothesis Engine

↓

Memory System

↓

Person Model

↓

Reflection Engine

↓

Question Engine

↓

Updated Cognitive State

---

# Component Responsibilities

## Interpretation Engine

Reads:

- Conversation
- Current Cognitive State

Produces:

- Candidate interpretations

Updates:

- Cognitive State

---

## Observation Model

Reads:

- Candidate interpretations
- Current Cognitive State

Produces:

- Structured observations

Updates:

- Active Observations

---

## Pattern Model

Reads:

- Active observations

Produces:

- Candidate patterns

Updates:

- Active Patterns

---

## Hypothesis Engine

Reads:

- Active patterns
- Evidence

Produces:

- Psychological hypotheses

Updates:

- Active Hypotheses
- Confidence
- Uncertainty

---

## Memory System

Reads:

- Confirmed hypotheses
- Confirmed observations

Produces:

- Long-term psychological memory

Updates:

- Memory

---

## Person Model

Reads:

- Memory
- Patterns
- Hypotheses

Produces:

- Current psychological representation

Updates:

- Person Model

---

## Reflection Engine

Reads:

- Complete Cognitive State

Produces:

- Psychological reflections

Updates:

- Recent Insights

---

## Question Engine

Reads:

- Cognitive State
- Uncertainty
- Missing Evidence

Produces:

- Clarifying questions

Updates:

- Open Questions

---

# Shared Cognitive State

Every component contributes to a shared Cognitive State containing:

- Person Model
- Memory
- Active Observations
- Active Patterns
- Active Hypotheses
- Confidence
- Uncertainty
- Open Questions
- Recent Insights

No component maintains an independent cognitive representation.

---

# Design Principles

Components are:

- modular;
- explainable;
- replaceable;
- evidence-driven;
- psychologically consistent.

Each component improves understanding without breaking existing knowledge.

---

# Closing Principle

The architecture is not a processing pipeline.

It is a cooperative cognitive system in which specialized components continuously refine a shared Cognitive State.

Understanding emerges from their interaction rather than from any individual component.
