    # Level 12 - Archive extraction

    ### Challenge
    Unpack nested compressed files to reach the password.

    ### Solution
    ```bash
    xxd -r data.txt data.gz
gunzip data.gz
tar -xf data.tar
bzip2 -d data.bz2
    ```

    ### What I Learned
    I worked through multiple compression formats step by step.

    ### Key Takeaway
    I can extract and inspect archives safely and methodically.
