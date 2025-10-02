    # Level 21 — Cron inspection

    ### Challenge
    Inspect system cron jobs and identify where passwords may be stored.

    ### Solution
    ```bash
    ls /etc/cron.d/
cat /etc/cron.d/cronjob_bandit22
    ```

    ### What I Learned
    Cron jobs often run scripts that hold or move data.

    ### Key Takeaway
    I check scheduler configurations for automated tasks.
