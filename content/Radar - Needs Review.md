---
created: 2025-01-05T22:22:00.000-05:00
modified: 2025-01-06T21:56:58.601-05:00
draft: true
---
These are the items that need to be reviewed:

```dataview
table tags, created as "Created", modified as "Modified"
from "radar"
where created < date(now) - dur("1 year") or contains(ring, "#needs-review")
sort Quadrant, Ring, title
```
