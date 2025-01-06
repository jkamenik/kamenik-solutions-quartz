---
ring: Hold
quadrant: "[[Tools]]"
movement: Unchanged
created: 2023-04-05T17:23:00
modified: 2025-01-05T22:28
tags:
  - quardrant/hold
  - ring/tool
---
> [!summary]
> A remote server automation and deployment tool written in Ruby.
>
> https://capistranorb.com/

## Assessment

While this tool helped to usher in the practice of DevOps using Ruby as a DSL in practice it ended up being anything but.  While defining pipelines with code seems like a panacea it ends up become yet another test surface without adequate testing frameworks.  It therefore becomes untestable and fragile and should be avoided.

Moderns [[IaC]] tools like [[Ansible]], [[Terraform]], and [[Kubernetes]] should be used instead.
