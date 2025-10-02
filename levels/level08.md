    # Level 08 — Find by owner

    ### Challenge
    Locate a file owned by a given user and matching size constraints.

    ### Solution
    ```bash
    find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
    ```

    ### What I Learned
    `find` can search system-wide by user, group, and size.

    ### Key Takeaway
    I search system areas when a user-owned artifact is needed.
