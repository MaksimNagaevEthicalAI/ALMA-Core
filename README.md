# ALMA Core

## Evidence-Based Cognitive Architecture for Long-Term Psychological Understanding

ALMA Core is the cognitive architecture powering the ALMA AI research initiative.

Rather than treating each conversation as an isolated interaction, ALMA is designed to build and continuously refine an evolving representation of a person from observations, evidence, patterns, hypotheses, and uncertainty.

The central idea is simple:

> **The conversation is the input.  
> The evolving understanding is the product.**

---

## Current Development Status

**ALMA is an active working research prototype.**

The core cognitive architecture has moved beyond the conceptual stage and is currently running as an integrated prototype with a live conversational interface.

Implemented capabilities include:

- Persistent cognitive models
- Evidence-based observations
- Hypothesis generation and revision
- Long-term memory across conversations
- Adaptive questioning
- Cognitive state restoration across sessions
- Persistent dialogue sessions
- User-specific cognitive state
- Evidence accumulation over time
- Confidence and uncertainty handling
- Conversation-aware reasoning
- Integration with an LLM-based conversational layer

The current system is being validated through live interaction and diagnostic testing.

The next stage is not to prove that the architecture can be implemented.

It is to determine whether it can produce a **coherent, evidence-based, revisable understanding of a person over time**.

---

## What ALMA Is Trying to Build

Most conversational AI systems are optimized to generate useful responses.

ALMA explores a different direction:

**Can an AI system gradually construct an internal model of a person that becomes more useful as evidence accumulates?**

The objective is not to diagnose a person or predict them from a single interaction.

Instead, ALMA works toward a persistent cognitive representation that can evolve as new conversations provide new evidence.

A conversation therefore becomes more than an exchange of messages.

It becomes another source of evidence.

---

## Cognitive Processing Pipeline

ALMA transforms conversational input into progressively richer cognitive representations:

**Conversation → Interpretation → Observation → Pattern → Hypothesis → Evidence Integration → Cognitive State → Adaptive Dialogue**

The system is designed so that new evidence can strengthen, weaken, revise, or challenge previous hypotheses.

This makes the cognitive model **dynamic rather than static**.

---

## Core Architecture

The architecture is organized around several cognitive components:

- Interpretation Engine
- Observation Model
- Pattern Model
- Hypothesis Engine
- Evidence Integration
- Confidence Assessment
- Psychological Model
- Cognitive State
- Reflection Engine
- Adaptive Question Generator
- Long-Term Memory
- Dialogue State Management

These components are intended to work together rather than function as isolated features.

---

## Evidence Before Conclusions

A fundamental design principle of ALMA is to separate:

**what was observed**

from

**what might explain the observation.**

The system therefore distinguishes between observations, patterns, hypotheses, and higher-level understanding.

This allows the model to remain revisable when new evidence appears.

ALMA does not need to be certain immediately.

It needs to become **better calibrated over time**.

---

## Longitudinal Understanding

The defining characteristic of ALMA is persistence.

A person should not have to start from zero every time a new conversation begins.

The system is designed to restore previous cognitive state and continue reasoning from accumulated evidence.

This creates the possibility of a fundamentally different interaction model:

**Conversation → Memory → Understanding → New Conversation**

Each interaction can contribute to the next one.

---

## Adaptive Dialogue

ALMA does not treat questioning as a fixed questionnaire.

Questions can be selected based on:

- previous observations
- existing hypotheses
- uncertainty
- missing evidence
- conversational context
- the current cognitive state

The purpose is not simply to ask more questions.

It is to ask questions that can meaningfully improve the model.

---

## Design Principles

- Evidence before conclusions
- Multiple competing hypotheses
- Explicit uncertainty representation
- Longitudinal memory instead of session-only memory
- Hypotheses remain revisable
- Adaptive questioning instead of fixed questionnaires
- Psychological understanding rather than diagnosis
- Reflection before recommendation
- Accumulation of evidence across conversations

---

## Research Direction

ALMA is ultimately exploring whether conversational AI can move from:

**response generation**

toward:

**persistent cognitive understanding.**

The key research question is not whether an LLM can sound psychologically insightful.

It is whether an architecture built around evidence, memory, hypotheses, uncertainty, and revision can maintain a useful and coherent understanding of a person over time.

That distinction is central to the project.

---

## Current Prototype

The current implementation connects the cognitive architecture to a working conversational system.

The prototype currently supports:

- Live dialogue
- Persistent user models
- Persistent conversation history
- Cognitive state restoration
- Adaptive dialogue
- Evidence and hypothesis processing
- Long-term memory
- LLM-assisted reasoning

The prototype is intentionally still under validation.

It is **not presented as a finished clinical, diagnostic, or production system**.

The purpose of the current stage is to determine whether the underlying cognitive architecture works in practice.

---

## Research Demonstrations

The ALMA research approach is also demonstrated through public synthetic research materials.

### Kaggle Dataset

A small synthetic dataset demonstrating the evidence-based reasoning structure used by ALMA:

**[ALMA AI — Evidence-Based Reasoning Demo Dataset](https://www.kaggle.com/datasets/almaairesearch/alma-ai-evidence-based-reasoning-demo-dataset/data)**

The dataset demonstrates the separation of:

**Observation → Evidence → Hypothesis → Confidence → Uncertainty → Revision**

It contains no private user conversations or personal data.

### Kaggle Notebook

An executable demonstration using the dataset:

**[ALMA AI — Evidence-Based Reasoning Demo](https://www.kaggle.com/code/almaairesearch/alma-ai-evidence-based-reasoning-demo)**

The notebook illustrates how evidence-based and revisable reasoning can be represented and examined programmatically.

### Interactive Prototype

An interactive demonstration of the ALMA AI prototype is available on Hugging Face:

**[ALMA AI — Hugging Face Space](https://huggingface.co/spaces/MaksimNagaevEthicalAI/alma-ai)**

The Space provides an accessible way to explore the current ALMA prototype and its cognitive architecture.

---

## Documentation

### Current Product Vision & Development

The most recent overview of the ALMA product direction, architecture, current implementation, and validation stage:

**[ALMA AI — Unified Product & Development Overview](docs/ALMA_AI_Unified_Partner_Overview_August_2026.pdf)**

### Architecture Documentation

See [`architecture/`](architecture/) for architectural and knowledge-representation materials.

### Project Documentation

See [`docs/`](docs/) for research and product documentation.

### Prototype

See [`prototype/`](prototype/) for prototype-related materials.

### ALMA Research

The broader research archive, including research papers, architectural documents, concepts, executive materials, and historical project documentation:

**[ALMA Research](https://github.com/MaksimNagaevEthicalAI/ALMA-Research)**

---

## Research Philosophy

ALMA is built around a simple principle:

> **Understanding should improve over time.**

Instead of trying to predict a person from limited information, the system continuously updates an evolving cognitive representation using observations, patterns, hypotheses, evidence, confidence, and interaction history.

Every meaningful conversation can therefore become additional evidence rather than an isolated event.

---

## Project Status

**Status: Active Research Prototype — August 2026**

The architecture is implemented and connected to a working conversational prototype.

Current work is focused on:

1. Validation of longitudinal cognitive understanding
2. Reliability of evidence and hypothesis formation
3. Adaptive dialogue quality
4. Cognitive state persistence and restoration
5. Product integration
6. Evaluation of whether the architecture produces meaningful improvement over time

The experiment is ongoing.

**This repository documents the architecture and its evolution as the system moves from research prototype toward an integrated product.**
