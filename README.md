# Choco AI Product Discovery Case Study

## Overview

This is an independent AI Product Management case study exploring how Choco could help food-distributor sales teams identify early signs of customer revenue decline and take action before revenue loss becomes material.

The project focuses on product discovery rather than jumping directly into an AI solution.

## Product Question

How might Choco help food-distributor sales teams identify meaningful early signs of customer decline and take the right action before revenue loss becomes material?

## Target User

Primary user:
Sales representative / Account Manager

Secondary user:
Sales Manager

Buyer:
Head of Sales / Commercial Lead / Distributor Owner

## Core User Problem

A sales rep managing a large portfolio of restaurant accounts may struggle to identify meaningful changes in purchasing behaviour early enough to act.

## JTBD

When I manage a large portfolio of restaurant customers, I want to understand which accounts require my attention and why, so that I can take the right action before meaningful revenue is lost.

## Key Assumption

Earlier identification of changing purchasing behaviour will lead to sales actions that materially recover revenue.

## Discovery Approach

1. Understand the current workflow
2. Separate facts from assumptions
3. Validate the problem through user research
4. Compare deterministic and AI-based solutions
5. Identify AI risks and guardrails
6. Test the riskiest assumption before building
7. Define model, product, business, and guardrail metrics

## Solution Options Considered

- Decline dashboard
- Rule-based alerts
- Weekly account digest
- Predictive risk model
- AI Sales Copilot

## Why AI?

AI may add value when customer risk depends on multiple interacting behavioural signals such as:

- order frequency
- basket value
- product category disappearance
- seasonality
- account history
- pricing changes
- historical recovery patterns

A predictive model could identify risk, while an LLM could explain the context.

Final commercial decisions remain human-controlled.

## Testing Approach

Before building a model, I would run a Wizard-of-Oz experiment using historical account data and evidence-backed account cards.

The goal is to test whether earlier signals actually change sales behaviour.

## Success Metrics

### AI quality
- Precision
- Recall
- Calibration

### Product behaviour
- Alert review rate
- Action rate
- Time to action
- Dismissal rate

### Business outcome
- Recovered revenue
- Retained revenue
- Reduction in avoidable churn
- Sales productivity

### Guardrails
- False-positive rate
- Unnecessary discounts
- Unwanted customer outreach

## Key Product Principle

Prediction → Understanding → Decision → Action → Business Outcome

Model performance alone does not equal product success.

## Disclaimer

This is an independent portfolio case study based on publicly available information and hypothetical assumptions. I am not affiliated with Choco.
