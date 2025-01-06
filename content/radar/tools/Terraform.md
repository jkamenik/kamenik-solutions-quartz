---
ring: Assess
quadrant: "[[Tools]]"
movement: Down
created: 2024-04-05T18:34
modified: 2025-01-05T22:30
---
# Terraform

https://www.terraform.io/

> Automate infrastructure on any cloud with Terraform

This has the been the defacto standard for [[IaC]] for quite some time.  However, it was knocked out of its Adopt status by the commercial license change.  This means that it has become to cost prohibitive for some companies, which have invested in other solutions.

There has been complaints for a long time that the declarative nature causes some simple use-cases to be impossible.  While that is less true with the templating additions to the [[HCL]] language, [[Terragrunt]] is a wrapper that nearly eliminates all complains, while remaining declarative.