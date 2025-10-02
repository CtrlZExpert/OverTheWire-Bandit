    # Level 01 - Reading files

    ### Challenge
    Find the password for the next level stored in a file named `-`.

    ### Solution
    ```bash
    ssh bandit1@bandit.labs.overthewire.org -p 2220
cat ./-
    ```

    ### What I Learned
    I learned how to handle files whose names look like options.

    ### Key Takeaway
    Small filename quirks can break scripts; I check the file path carefully.
