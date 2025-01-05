---
ring: Assess
quadrant: "[[Tools]]"
movement: Up
created: 2024-04-05T17:50
updated: 2024-04-07T13:40
---
# Pulumi

https://www.pulumi.com/

> Build and ship faster using open source infrastructure as code


> [!NOTE] Use [[Terraform]], if you can
> If you lived in a vacuum you might not be aware that this project a direct response to commercial license change that Hashicorp did to monetize use of Terraform by larger companies.  Politics aside, at the time of this update Terraform is still the better solution and should be used it you can.

Like [[Capistrano]] before it Pulumi uses procedural programming to define infrastructure.  This is fraught with issues, that should make this a hard Hold.  However, this takes a page out of Terraform playbook and hides many of the implementation details within its standard library making it a bridge between imperative and declarative.

If you are in a company that cannot use Terraform and you have a mature enough team actively avoid the pitfalls of imperative programming (error handling, retries, data normalization, etc...) then this is a very competent solution.  Otherwise steer clear because you are going to end up in a worst place just building by hand.
