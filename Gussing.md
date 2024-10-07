flowchart TD
    A[Generating a Random Number...]-->
    B@{ shape: paper-tape, label: "Hint: The Price of a sealed and autographed copy of __The Room__ by Tommy Wiseau on Bluray."}

    B --> C{What number is it?}
    C --> D([Input < $399])
    C --> E([Input = $399])
    C --> F([Input > 399])

    D --> G[Too Low!]
    E --> I[Correct!]
    F --> H[Too High!]

    G --> C
    H --> C

    I--> J[Generating a Random Number...]
