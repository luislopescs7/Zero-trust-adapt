# Scoring Model

## Overview

The scoring model is used to evaluate the organisation’s security maturity across each domain based on survey responses.

Each answer corresponds to a maturity level, allowing the system to calculate a structured score and classify the organisation’s current posture.

---

## Scoring Scale

Each question is scored from 0 to 5:

- 0 → Not implemented
- 1 → Minimal / insecure implementation
- 2 → Basic implementation
- 3 → Standard practice
- 4 → Advanced implementation
- 5 → Fully aligned with Zero Trust principles

---

## Domain Scoring

Each domain (Users, Endpoints, Networks, etc.) contains multiple questions.

The domain score is calculated by:

- Summing all answers within the domain
- Calculating the average score

This produces a maturity score between 0 and 5 for each domain.

---

## Maturity Levels

Based on the score, each domain is classified as:

- 0.0 – 1.5 → Basic
- 1.6 – 2.5 → Developing
- 2.6 – 3.5 → Intermediate
- 3.6 – 4.5 → Advanced
- 4.6 – 5.0 → Zero Trust Aligned

---

## Overall Maturity

An overall maturity score is calculated by averaging all domain scores.

This provides a high-level view of the organisation’s security posture.

---

## Decision Logic

The scoring model drives the recommendations:

### Low Scores (0–2)
- Focus on foundational controls
- Introduce missing security measures

### Medium Scores (2–4)
- Improve and optimise existing controls
- Reduce gaps and inconsistencies

### High Scores (4–5)
- Fine-tuning and automation
- Alignment with Zero Trust architecture

---

## Purpose

The scoring model ensures that:

- Recommendations are consistent and structured
- Different organisations receive tailored outputs
- The system can scale and be automated in the future

It transforms qualitative answers into measurable and actionable insights.
