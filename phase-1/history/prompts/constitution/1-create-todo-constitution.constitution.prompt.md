---
id: 1
title: Create Todo Constitution
stage: constitution
date: 2026-02-04
surface: agent
model: Claude Sonnet 4.5
feature: none
branch: main
user: SHARJEELAHMED
command: /sp.constitution
labels: [constitution, todo-app, setup]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
 - .specify/memory/constitution.md
tests:
---
## Prompt

```text
You are Claude Code operating as a senior Python engineer and spec-driven development agent.

Your mission is to design and implement a basic-level, in-memory Python console application using a strict Spec-Driven Development workflow powered by Spec-Kit Plus.

====================================
PROJECT OBJECTIVE
====================================

Build a command-line Todo application that:
- Stores all data in memory (no persistence)
- Demonstrates clean architecture and code quality
- Implements all required basic features
- Is developed entirely through specs, plans, tasks, and agentic execution

No manual coding is allowed outside of Claude Code execution.

====================================
CORE PRINCIPLES
====================================

- Spec-first development is mandatory
- No implementation before specification
- Each phase must be reviewable and auditable
- Favor clarity and simplicity over cleverness
- Follow clean code and Python best practices

====================================
REQUIRED FEATURES
====================================

The application must support:
1. Add a task (title + description)
2. View all tasks with status indicators
3. Update task details
4. Delete a task by ID
5. Mark tasks as complete or incomplete

====================================
FINAL DELIVERABLE
====================================

A working Python console application that:
- Runs via CLI
- Uses in-memory storage
```

## Response snapshot

Updated the project constitution with appropriate principles for the Todo console application, focusing on specification-first development, in-memory storage, clean architecture, test-first approach, console interface standards, and minimalist feature set.

## Outcome

- ✅ Impact: Created project constitution file with 6 core principles for the Todo application
- 🧪 Tests: No tests created in this phase
- 📁 Files: Updated .specify/memory/constitution.md with appropriate principles
- 🔁 Next prompts: Proceed with specification phase using /sp.specify
- 🧠 Reflection: Constitution properly established foundation for Spec-Driven Development workflow

## Evaluation notes (flywheel)

- Failure modes observed: None
- Graders run and results (PASS/FAIL): PASS - Constitution follows required template and principles
- Prompt variant (if applicable): N/A
- Next experiment (smallest change to try): Begin specification phase with /sp.specify