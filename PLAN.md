# Project Plan
> **AI Instruction:** Treat this file as the absolute source of truth for the project's state. When asked what we are building or what the next steps are, refer to this document.

## Vision Statement
[Describe the project in 2–3 sentences. What does it do? Who is it for? What is the core value proposition?]

## Scope & Constraints
- **In scope:** [List core features, flows, or modules.]  
- **Out of scope:** [List things explicitly excluded.]  
- **Constraints:** [Tech stack, latency, security, compliance, or infra limits.]

## System Architecture
- **Core Entity:** [Description]  
- **Data Flow:** [Description]  
- **Primary Interfaces:** [APIs, UIs, CLI, etc.]  
- **Key Dependencies:** [External services, libraries, infra.]

## Roadmap
> Use `[x]` for finished items, `[/]` for items currently being worked on, and `[ ]` for future tasks.

### Phase 1: MVP Core
- `[ ]` Define or update `rules/architecture.md`  
- `[ ]` Set up project skeleton (repo, linting, CI, etc.)  
- `[ ]` Implement core feature X  
- `[ ]` Implement basic security posture (auth, logging, secrets handling)

### Phase 2: Refinement
- `[ ]` Write unit and integration tests  
- `[ ]` Finalize comments, docs, and `README.md`  
- `[ ]` Optimize performance and error‑handling  
- `[ ]` Polish UX / CLI UX

### Phase 3: Hardening & Observability
- `[ ]` Add logging, metrics, and alerts  
- `[ ]` Run security‑oriented review (e.g., secrets, auth, input validation)  
- `[ ]` Stress‑test or load‑test critical paths, if applicable

## Current Execution Status
- **Current Task:** [Task you are working on right now]  
- **Recent accomplishment:** [What was just finished last session]  
- **Blocked By:** [Waiting on infra, human decision, API, etc.]  
- **Next Steps (next 1–3):**  
  1. [Next small, concrete step]  
  2. [Next small, concrete step]  
  3. [Next small, concrete step]

## Risks & Assumptions
- **Key risks:** [e.g., API instability, unclear UX, infrastructure delays]  
- **Assumptions:** [e.g., “API X will be available by date Y”, “User accepts terms via agreed flow”]

*Note to Human: Update “Current Execution Status” and “Risks & Assumptions” at the end of every programming session. Use `PROJECT_PLAN.md` + `agent_logs/*` + `rules/` to keep agents aligned.*
