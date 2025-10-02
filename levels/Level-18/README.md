# Level 18 — Non-interactive SSH

### Challenge
Run a command remotely without an interactive shell.

### Solution
```bash
ssh bandit18@bandit.labs.overthewire.org -p 2220 "cat readme"
```

### What I Learned
I learned to run single commands over SSH directly.

### Key Takeaway
Non-interactive SSH is useful for automation and scripting.
