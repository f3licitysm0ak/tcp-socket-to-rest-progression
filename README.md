**Progression from TCP socket client-server programming to HTTP/RESTful mini-service.** <br>

A step-by-step progression from low-level TCP socket programming to building a RESTful HTTP-like mini-service.
---

## Overview

* **`milestone-1` — Basic Socket Echo**
  Simple TCP client-server socket program implementing a basic echo protocol.

* **`milestone-2` — Length-Prefixed Framing**
  Sends the message length before the payload so the receiver knows exactly how many bytes to read.

* **`milestone-3` — Command Processing**
  Receives messages, parses command lines (e.g., `ECHO`, `TIME`), and sends back execution results.

* **`milestone-4` — Structured Protocol Parsing**
  Implements structured message parsing with headers and content bodies, moving closer to a real wire protocol.

* **`milestone-5` — RESTful HTTP Mini-Service**
  Implements HTTP/REST-like request formatting and delivers JSON-formatted responses.
