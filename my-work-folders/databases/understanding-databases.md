---
description: A more technical understanding of how databases work
---

# Understanding Databases

Internally, Lucy uses `MongoDB` (or a MongoDB-compatible service) as its storage engine for collections. Consequently, many standard MongoDB semantics apply to databases.

This includes:

* Every document has a `_id` field that is generated automatically.
* The ability to run custom MongoDB-compatible queries on your database.
