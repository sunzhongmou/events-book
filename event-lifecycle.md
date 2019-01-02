---
description: What's the lifecycle we recommend for a event
---

# Event lifecycle

When to publish?

* Domain change Event
* Retroactive Event
  * out-of-order event
  * rejected event
  * incorrect event
* Group Event: buffering multiple updates for a event

How to logging?

* Event sourcing & Event log in source system

What to log?

* Event id
* Domain id
* Event name
* GDPR perspective

Event architectural constraint:

* Idempotency as key: publish the same event should not cause any sub system issue
* Time Zoom?
* From publisher Backwards compatibility pattern expected
* From subscriber Tolerant reader pattern expected
* Fault tolerant from different level, 4XX should pause all the queue
* Anti Pattern

\*\*\*\*

\*\*\*\*

