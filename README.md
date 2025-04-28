# RunBTC Backend

Notes:
- axum for server & tokio for the  REST server/async runtime
- DB: Postgres or Elastic Search (https://www.youtube.com/watch?v=ZP0NmfyfsoM&ab_channel=IBMTechnology)
- Authentication: Warp + JWT (Use Refresh tokens and/or Short lived tokens) (RSA+ECDSA is more secure than HMAC)
- serde and serde_json for JSON
- tracing and tracing-subscriber for logging
