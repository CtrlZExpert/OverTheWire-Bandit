# Level 07 — Binary to text

### Challenge
Extract readable text from a binary file to find the password.

### Solution
```bash
strings data.txt | grep password
```

### What I Learned
`strings` extracts human text from binaries.

### Key Takeaway
I can parse messy files to find useful strings.
