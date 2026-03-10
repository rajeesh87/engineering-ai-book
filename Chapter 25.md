# Agents and Tool-Using AI Systems

## What an Agent Is

An AI agent is a system that can plan, call tools, observe results, and iterate toward a goal under constraints.

## Agent Components

- Planner (task decomposition)
- Tool registry (APIs, databases, code execution)
- Memory (session and long-term state)
- Policy layer (permissions, safety rules)
- Evaluator (checks whether output meets criteria)

## When to Use Agents

Use agents when tasks require:
- multi-step workflows,
- dynamic tool selection,
- external actions,
- iterative verification.

Do not use agents for simple one-shot generation.

## Multi-Agent Patterns

- Router agent + specialist agents
- Critic/reviewer agent for quality checks
- Executor agent with strict permissions

## Risks and Controls

- runaway tool loops,
- unsafe tool calls,
- hidden prompt injection via tools,
- poor observability.

Mitigate with budgets, stop conditions, approval gates, and full tracing.

## Beginner Project

Create an "engineering research agent" that:
1. searches approved sources,
2. summarizes findings,
3. outputs references and confidence.

## Chapter Summary

Agents are powerful when constrained by explicit policies and strong observability.
