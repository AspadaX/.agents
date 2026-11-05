---
name: create-architect-diagram
description: Use this when the user wants to create a software architect diagram.
allowed-tools: Read
---

## Rules
- Find the entry point of the codebase first. If the user had provided one, use that instead.
- Output a mermaid script.
- The nodes on the diagram should be derived from the codebase's real structs, classes, modules, functions, constants, and so on.
  - Be object oriented when creating a diagram.
  - Never use concepts you created for the nodes.
- Review your diagram on completion and then fix the issues. 
