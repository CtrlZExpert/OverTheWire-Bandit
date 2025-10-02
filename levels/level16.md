    # Level 16 — Port discovery

    ### Challenge
    Find an open port in a range and connect securely.

    ### Solution
    ```bash
    nmap -p 31000-32000 localhost
openssl s_client -connect localhost:31790
    ```

    ### What I Learned
    Port scanning helps locate hidden services.

    ### Key Takeaway
    I combine scanning and secure clients to explore network services.
