---
created: 2025-01-05T22:22
modified: 2025-01-05T22:43-05
draft: true
---
These are the items that need to be reviewed:

```dataview
table tags, created as "Created", modified as "Modified"
from "radar"
where created < date(now) - dur("1 year") or contains(ring, "#needs-review")
sort Quadrant, Ring, title
```
