    # Level 20 - Process communication

    ### Challenge
    Send data to a service and receive a response using local networking.

    ### Solution
    ```bash
    echo "password" | nc -l -p 1234 &
./suconnect 1234
    ```

    ### What I Learned
    I learned to pipe data between processes and network sockets.

    ### Key Takeaway
    Inter-process communication is key when services interact.
