## 2024-03-27 - [CSWSH Protection]
**Vulnerability:** Local WebSocket IPC server allowed connections from any origin, making it vulnerable to Cross-Site WebSocket Hijacking (CSWSH) from malicious websites.
**Learning:** Browsers automatically attach the Origin header to cross-origin WebSocket requests.
**Prevention:** Rejecting incoming WebSocket connections that contain an Origin header prevents browsers from interacting with the local IPC server.
