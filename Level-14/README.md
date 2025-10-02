# Level 14 — Netcat transfer

### Challenge
Send the password to a service listening on a port.

### Solution
```bash
cat /etc/bandit_pass/bandit14 | nc localhost 30000
```

### What I Learned
`nc` (netcat) is useful to send and receive raw network data.

### Key Takeaway
Netcat is a lightweight tool for testing services and ports.
