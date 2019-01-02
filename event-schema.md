---
description: >-
  What's the schema of the event, so that everyone will understand what's the
  event means, and what I should do.
---

# Event schema

* Metadata
* Payload
  * Unique Identifier, type string and TimeUUID
  * Domain Identifier
  * Event notification: there is no reaction happens in subsystem, and the source system should support query
  * Event-Carried state transfer: changes include, not the further changes, but the fact changes
  * Event order
* Version



**Fine Grained VS Coarse Grained**

**Fine Grained** with CRUD details, we will end up with too many events

**Coarse Grained**, how could we help people to understand and maintain it easily? May be we could thinking about naming, subdomain and Schema.

