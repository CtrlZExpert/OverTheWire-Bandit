# Level 09 — Pattern search

### Challenge
Search within a file for a recognizable pattern that holds the password.

### Solution
```bash
strings data.txt | grep '==\|password'
```

### What I Learned
Using `grep` finds patterns fast.

### Key Takeaway
Pattern matching reduces manual scanning time.
