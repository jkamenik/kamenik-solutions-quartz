---
created: 2025-01-05T01:10
modified: 2025-01-05T22:46-05
tags:
  - quardrant/hold
  - ring/technique
description: Don't Repeat Yourself is a technique aimed at reducing repetition of code.
---
> [!summary]
> Don't Repeat Yourself is a technique aimed at reducing repetition of code.
>
> https://en.wikipedia.org/wiki/Don%27t_repeat_yourself

## Assessment

While the assertion that repeated code is harder to maintain and therefore error prone is true, the way that DRY is implement is often wrong and leads to increasingly complex code with more abstractions then necessary.  It also lead to premature optimization and various other anti-patterns which increase the blast radius of changes.

In the IaC world minimizing blast radius is paramount.  Therefore a little repeated code here and there is a small price to pay for a robust infrastructure.

## Resources

- https://dev.to/ralphcone/please-do-repeat-yourself-dry-is-dead-1jbg
- https://dev.to/jeroendedauw/the-fallacy-of-dry