    # Level 24 - Automation & loops

    ### Challenge
    Automate a repetitive test (numeric brute-force) to find the password.

    ### Solution
    ```bash
    for i in {0000..9999}; do
  echo $i
  echo $i | nc localhost 30002
done
    ```

    ### What I Learned
    Simple loops can test many inputs quickly.

    ### Key Takeaway
    Automation helps when a task is repetitive and safe to run.
