---
name: create-architect-diagram
description: Use this when the user wants to create a software architect diagram.
---

## MermaidCLI
- Use `https://github.com/mermaid-js/mermaid-cli` to visually comprehend the diagram you created.
- If the user had installed mermaid-cli already, use it directly. Otherwise, install it for the user.

## Rules
- Find the entry point of the codebase first. If the user had provided one, use that instead.
- Output a mermaid script.
- The nodes on the diagram should be derived from the codebase's real structs, classes, modules, functions, constants, and so on.
  - Be object oriented when creating a diagram.
  - Never use concepts you created for the nodes.
- When creating diagrams, you should place relevant nodes together and leave enough spacing between nodes.
  - If you there are certain parts on the diagram is too dense, you should reconsider your placement.
- Review your diagram on completion and then fix the issues.
  - You should also review it visually using `MermaidCLI`. Never skip this.
