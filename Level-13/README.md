# Level 13 — SSH keys

### Challenge
Use a private SSH key file to log in to the next level.

### Solution
```bash
ssh -i sshkey.private bandit14@localhost -p 2220
```

### What I Learned
SSH keys let me authenticate without passwords.

### Key Takeaway
Keys are standard for automation and secure access.
