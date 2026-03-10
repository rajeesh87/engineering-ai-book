# LLMOps: Shipping and Operating LLM Systems

## What LLMOps Covers

LLMOps is the operational discipline for developing, evaluating, deploying, and continuously improving LLM applications.

## LLMOps Lifecycle

1. Define product behavior and risk boundaries.
2. Build prompts/retrieval/tools.
3. Evaluate quality offline.
4. Deploy with feature flags and canary rollout.
5. Monitor quality, safety, latency, and cost.
6. Iterate with feedback and regression tests.

## Core Practices

- Version prompts and system instructions.
- Maintain evaluation datasets and golden tests.
- Track online metrics and user feedback.
- Run red-team tests for jailbreak and injection risks.
- Automate rollback on quality regressions.

## Essential Metrics

- task success rate,
- groundedness/citation correctness,
- refusal correctness,
- latency p95,
- cost per successful task.

## Team Responsibilities

- Product: define use-case outcomes and acceptance metrics.
- Engineering: reliability, architecture, and observability.
- AI/ML: model and retrieval quality tuning.
- Security and legal: data controls and policy.

## Beginner Project

Set up a lightweight LLMOps checklist and release process for one internal assistant:
- pre-release eval gate,
- production telemetry dashboard,
- weekly quality review loop.

## Chapter Summary

Without LLMOps, AI features drift into unreliable demos. With LLMOps, they become dependable products.
