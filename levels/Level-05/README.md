# Level 05 — Searching files

### Challenge
Find the readable file that contains the password among many files.

### Solution
```bash
find inhere/ -type f -readable ! -size 0 -exec cat {} \;
```

### What I Learned
`find` helps filter files by many criteria.

### Key Takeaway
I use `find` to narrow down possible sources quickly.
