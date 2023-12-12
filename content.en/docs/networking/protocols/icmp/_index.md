---
title: ICMP
type: docs
weight: 3
bookToc: true
---

## ICMP (Internet Control Message Protocol)

is a supporting protocol used by network devices like routers for sending error messages and operation informations.

* Since IP does not have builtin mechanism for sending errors and controll messages, it relays on protocols like ICMP

we can use it for
TraceRoute(routes between two connected devices) and Ping(የገደል ማሚቱ time it took for echo messages reach and comeback)

* it doesn't need need to establish connection before hand, so it means it is not associated with transfer layer(UDP, TCP)

