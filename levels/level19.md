# Level 19 — setuid binaries

### Challenge
Use a provided binary with setuid to read a protected file.

### Solution
```bash
./bandit20-do cat /etc/bandit_pass/bandit20
```

### What I Learned
Setuid binaries run with the owner's permissions.

### Key Takeaway
I understand privilege boundaries and how system binaries can elevate access.
