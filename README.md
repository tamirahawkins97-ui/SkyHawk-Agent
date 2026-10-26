# SkyHawk - AI surveillance and governance agent

## Overview

This project implements a **duty-oriented autonomous agent** architected to operate strictly within the defined scope of its assigned responsibilities. Rather than reacting to isolated commands, the agent aligns its behavior to a top-level mandate. Within that primary scope, it dynamically decomposes responsibilities into subsidized, task-specific queries—ensuring consistent objective alignment, bounded authority, and deterministic execution.

### Operational Performance
- **Mandate-Driven Autonomy:** Evaluates all user inputs against its operational charter, ensuring every spawned action directly serves its core responsibilities.

- **Subsidized Query Generation:** Autonomously spins up, executes, and validates discrete task queries subordinate to the broader duty without drifting out of scope.

- **Scope & Context Integrity:** Maintains a bounded memory space that preserves duty parameters, environmental constraints, and interaction states across sessions.

- **Contextual Tool Routing:** Determines tool usage and external integrations strictly according to the permissions and needs of the active duty scope.

### Problem-Solving Framework
The agent approaches problems through a top-down, duty-governed lifecycle:

1. **Scope Validation & Intake:** Ingests external inputs and verifies whether the requested outcome falls within its operational domain.

2. **Duty Decomposition:** Breaks down the high-level responsibility into structured sub-tasks, framing each as a specialized, context-aware query.

3. **Subsidized Task Execution:** Dispatches each query to local tools, APIs, or data parsers, aggregating results under the supervising duty protocol.

4. **Outcome Verification:** Evaluates synthesized findings against the original duty criteria before returning a final state or response.

### Execution Standards
- **Bounded Determinism:** Rejects actions or queries that violate the scope of duty, preventing hallucinated scope creep.

- **Hierarchical Traceability:** Every subsidized task query leaves an auditable execution footprint linked back to the originating duty.

- **Defensive Execution:** Implements strict validation, timeout ceilings, and recovery protocols so individual task failures never compromise the agent's overall operational integrity.