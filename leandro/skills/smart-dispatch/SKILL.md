---
name: smart-dispatch
description: Automatically routes tasks to optimal Claude models (opus/sonnet/haiku) based on complexity. Use when implementing features, fixing bugs, or any multi-step development work. Trigger whenever a task can be broken into subtasks of different complexity levels — architecture decisions, business logic implementation, or mechanical/boilerplate generation.
---

# Smart Model Dispatch

Route each subtask to the model with the best cost-benefit ratio. The goal is to reserve heavy compute for decisions that actually need it, and use fast/cheap models for mechanical work.

## Model Routing Rules

### opus — Complex reasoning & architecture
- Architecture planning and design
- Complex business logic implementation
- Feature planning and requirement analysis
- Decisions with long-term consequences or many tradeoffs

### sonnet — Standard implementation
- Business logic (use cases, repositories, stores)
- Screen/component implementation with logic
- API/database integration
- Code reviews and refactors with meaningful logic

### haiku — Fast, mechanical tasks
- Generating style files (`.styles.ts`, CSS modules, etc.)
- Writing i18n / translation files
- Creating boilerplate and mocks
- Writing unit tests
- Renaming, formatting, simple search-and-replace

## Dispatch Pattern

When given a multi-step task, break it into subtasks and assign a model to each. Spawn parallel subagents where subtasks are independent.

**Example — Implement Watchlist feature:**

```
1. [opus]   Plan architecture (data model, layers, edge cases)
2. [sonnet] Implement domain + data layers
3. [sonnet] Implement screen with ViewModel
4. [haiku]  Generate .styles.ts, i18n keys, mocks
5. [haiku]  Write unit tests
```

Steps 2–5 can run in parallel after step 1 completes.

## Key Principle

Don't use Opus where Haiku suffices. Don't use Haiku where Sonnet is needed. Match the model to the cognitive demand of the task — not the importance of the feature.
