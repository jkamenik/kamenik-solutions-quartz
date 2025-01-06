---
date: 2025-01-05
tags:
  - quardrant/hold
  - ring/technique
created: 2025-01-05T00:33
updated: 2025-01-05T01:06
---
> [!danger]
> Avoid if possible and use Declarative [[IaC]] instead.

## Assessment

The number one complaint about IaC tools like [[Terraform]] is that they are not [[DRY]] enough.  That is, if you have many object to create, you have to create them all by hand, and thus being able to use programmatic constructs to reduce the that manual duplication should be a good things.

Unfortunately, [[DRY]] increases your blast radius, which increases the chance that a minor change will happily destroy production workloads in a difficult to recovered way.  Most companies (or programmers for that matter) don't have the maturity to catch all edge cases introduced by the power of fully baked programming languages.  And thus the problems introduced by this kind of technique far out weigh any benefits.

The fact that [[Pulumi]] and [[AWS CDK]] are becoming popular is simply history repeating itself.  We are likely to continue to hear about outages caused by "edge cases" as these tools become more widely used.  So it is best to avoid them if you can.