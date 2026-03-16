<!-- ai-context-orchestrator:generated:start -->
## AI Context Orchestrator

- Workflow preset: build
- Roles prepared: architect, implementer, reviewer, tester
- Refresh mode: smart-refresh
- Cost profile: balanced
- Context file: .ai-context.md
- Context budget profile: gemini-balanced
- Context budget summary: treeDepth=2, entries=28, readmeLines=20, instructionLines=80, deps=10, devDeps=8, scripts=8, keyFiles=8, instructionFiles=4

### Context First
Use the generated context pack as the primary source of truth for repository structure, key files, commands, and constraints.
This run uses a bounded context budget: treeDepth=2, entries=28, readmeLines=20, instructionLines=80, deps=10, devDeps=8, scripts=8, keyFiles=8, instructionFiles=4.
Prefer direct, well-structured reasoning with grounded file evidence over speculative expansion.

### Operating Style
- Keep the workflow explicit instead of blending exploration, planning, implementation, and review together.
- Work in short iterations and reassess after each concrete finding or edit.
- Prefer stable project patterns and minimal edits over flexible abstractions.

### Task
Read the imported sources for the selected compte-rendu, extract the useful material, reformulate it when needed, and integrate it cleanly into the existing document structure.

### Preset Priorities
- Validate the plan quickly, then move toward a minimal end-to-end implementation milestone.
- Keep verification focused and explicit before stopping.

### Completion Criteria
- Stop once the requested path is implemented and verified with the smallest relevant checks.
- Call out any remaining risks or intentionally deferred work.

### Avoid
- Do not expand scope into unrelated cleanup or architecture changes.
- Do not stop at partial implementation when a narrow end-to-end slice is achievable.

### Key files
- cours_systemes_avioniques.html
- GEMINI.md

### Useful commands
No package scripts detected.

### Instruction files already present
No provider-specific instruction files were detected during generation.
<!-- ai-context-orchestrator:generated:end -->
