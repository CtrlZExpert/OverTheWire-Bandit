# Level 15 — OpenSSL client

### Challenge
Connect to an SSL/TLS service and read the response.

### Solution
```bash
openssl s_client -connect localhost:30001
```

### What I Learned
`openssl` can make TLS connections and inspect certificates.

### Key Takeaway
I can inspect encrypted services and validate connections.
