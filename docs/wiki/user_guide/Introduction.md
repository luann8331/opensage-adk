# Introduction

## What is OpenSage-ADK?

OpenSage-ADK is an AI agent framework built on top of Google ADK. It represents a paradigm shift from "Agent Development 1.0" to "Agent Development 2.0" — transitioning from agents that execute predefined structures to agents that can dynamically build and manage their own systems at runtime.

**Agent Development 1.0** (Traditional ADK):

- Human-centric agent construction
- Agent structure is fully pre-defined by humans and fixed at runtime (topology, workflows, tool sets)
- Limited generalizability and adaptability, requiring extensive human effort

**Agent Development 2.0** (OpenSage-ADK):

- AI-centric agent construction
- Humans provide only minimal scaffolding
- Everything else is dynamically generated and managed by AI at runtime
- Agents can invent new capabilities rather than using the ones defined by human

## Key Features

- **Self-generated agent topology**: The agent can dynamically create, execute, and terminate sub-agents during task execution, supporting both vertical topology (decomposing a complex task into sequential sub-tasks handled by specialized sub-agents) and horizontal topology (multiple parallel agents execute the same task, then merge results via agent ensemble).

- **Dynamic tool and skill synthesis**: The agent can create tools and skills during execution. Our ADK provides a sandboxing system that enables tool-isolated execution and state management.

- **Hierarchical memory management**: File-based memory for both long-term (cross-task) and short-term (per-task) memory, with a built-in dedicated memory agent that can be enabled with a single line of code.

<!-- - **Other features**:
  - **Composability**: Build complex agents from simple components
  - **Flexibility**: Easy to add new tools, sandboxes, and agents
  - **Evolution**: Tools and agents can be created and modified at runtime
  - **Isolation&Scalability**: Kubernetes support (under development) -->

## Next Steps

- [Setup](Setup.md) - Set up your development environment
- [Project Structure](../developer_guide/Project-Structure.md) - Understand the
  codebase layout
- [CLI Reference](../cli/index.md) - Browse the CLI entry points and flags
- [Evaluations](../evaluation/index.md) - Understand the evaluation entry point
