# Level 11 — ROT13 decoding

### Challenge
Decode text that is encoded with ROT13.

### Solution
```bash
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```

### What I Learned
`tr` can perform simple character transforms like ROT13.

### Key Takeaway
Simple ciphers can still appear; I know how to decode them.
