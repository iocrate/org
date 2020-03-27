# TODO Network Development

## Aims

Build out-of-the-box network infrastructure, covering three to seven network programming environments.

## Contents

- [ ] Use `asyncdispatch` and `nativesockets`as the base IO engine, don’t use `asyncnet`, `asynchttpserver`, `httpclient`, and  `net`. Create an IO framework, including `net` module (TCP socket and TCP server), `datagram` module (UDP socket), `tls` module (TLS TCP socket and TLS TCP server), `http` module (HTTP client, HTTP server), `https` module (TLS http client and TLS http server), cutting test optimization `asyncdispatch` and `websocket` module.
- [ ] Build http toolkit including `cookie`, `session` (simple test environment), `formdata`, `openauth`, `jwt`.
- [ ] Build mainstream database connectors such as `mysql`, `postgresql`, `mongodb`, `redis`, supporting general request query, data flow, large result dataset and connection pools.
- [ ] Build a high-level web server framework that supports IOC, AOP / Interceptor, Validation, Logging, Testing (spring-boot / MVC style).
- [ ] Build a high-level SQL framework dependency injection framework.
- [ ] Build IMCP instant communication protocol, establish server, client, web client, android client.
- [ ] Build QUIC server and client.
- [ ] Build MQTT broker and client.
- [ ] Build a documentation website, including API documentation, tutorial list, key example list, benchmark link list, problem link list, link all network related content and dependent code library related materials together.

## Requirements

- Establish `iocrate `org which only stores an org organization description and other code libraries that are decided to be released, and does not store any other unrelated libraries.
- Each codebase undergoes multiple rigorous tests, benchmarks, and tests on multiple platforms / environments.
- Each codebase has API documentation.
- Each codebase has step by step instructions.
- Each codebase has key examples to demonstrate.
- Each codebase can timely feedback issues and fix bugs.
- Each codebase has maintainers.
- Documentation and website are available in Chinese and English.
