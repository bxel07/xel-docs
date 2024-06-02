<!-- TODO: Update with your values. -->
# XEL Documentation
!> This Framework still in experimental, dont use it on production



## What is Xel ? 
Xel is a high-performance, event-driven PHP framework built on top of the Swoole extension. It leverages Swoole's coroutine support, enabling asynchronous and non-blocking I/O operations, resulting in enhanced performance and concurrency. Xel incorporates the Gemstone Sub Layer, a central security abstraction layer that provides a separation of concerns and a unified point for implementing various security features. These features include protection against Distributed Denial of Service (DDoS) attacks, rate limiting mechanisms, Cross-Origin Resource Sharing (CORS) setup, and isolation sandboxes for running service logic in a secure and isolated environment. The Gemstone Sub Layer acts as a gatekeeper, safeguarding the application from potential security threats while ensuring efficient and secure execution of the core business logic.

## Requirements
- PHP version `>= 8.2`
- Swoole version `>=5.0`
- PHP dev tools


## Installation 
```composer
composer create-project xel/skeleton

```
After instalation success, run this command bellow to start server
```bash
php xel start
```
