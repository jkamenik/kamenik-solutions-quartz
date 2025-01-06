---
date: 2025-01-05
tags:
  - quardrant/adopt
  - ring/tool
aliases:
  - Declarative IaC
created: 2025-01-05T00:45
modified: 2025-01-05T22:30
---
> [!summary]
> Infrastructure as Code (IaC) is the idea that all infrastructure can (and should) be described as executable code.  This allows machines to continually reconcile the code against reality and eliminate drift before it becomes costly.

## Assessment

There are really 2 types of IaC:
- Declarative IaC - The end-state is declared and it is up to the tool to figure out how to drive that end state.
- [[Imperative IaC]] - Uses computer logic to define an end-state before handing that off to another tool to drive the end state.

Of the two only Declarative IaC is worthy of adoption, so stick with tools like [[Terraform]] and [[Ansible]] over others.

If you are annoyed by how not [[DRY]] IaC is then consider refactoring into versioned modules, or use something like CoPilot to generate the repetitive code.