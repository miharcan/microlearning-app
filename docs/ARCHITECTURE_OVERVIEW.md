# Architecture Overview (Public)

This is a high-level, non-sensitive view of how the product behaves.

## Core Loop
1. Context signal detected (time/window/readiness)
2. Session policy decides whether to intervene
3. Learner starts short session (smart or quick)
4. Answers update retention and mastery state
5. Insights summarize progress and due review load

## High-Level Flow
```text
Context Window -> Intervention Decision -> Session Start -> Response Signals -> Progress/Insights
```

## Design Principles
- Opportunity-first timing: intervene only when useful.
- Low-friction action: start learning in seconds.
- Memory-first outcomes: retention and recall over vanity engagement.
- Learner control: clear settings and intervention controls.
- Privacy-aware boundaries: public showcase separate from proprietary internals.

## Not Included Here
- Production architecture internals
- Ranking/scoring thresholds
- Quality-gate implementation details
- Private infrastructure and data operations
