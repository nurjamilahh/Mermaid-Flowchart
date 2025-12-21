```mermaid
graph LR
    A([Start Game]) --> B[/Player Selects Rock, Paper, or Scissors/];
    B --> C[Computer Generates Random Choice];
    C --> D{Compare PlayerChoice vs. ComputerChoice};
    D -- Is it a Tie? --> E[Declare: It's a Tie!];
    D -- Player Wins? (e.g., Rock vs. Scissors) --> F[Declare: You Win!];
    D -- Player Loses? --> G[Declare: Computer Wins!];
    E --> H(Display Result and Update Score);
    F --> H;
    G --> H;
    H --> I{Play Again?};
    I -- Yes --> B;
    I -- No --> J([End Game]);

%% Tambahkan Style di sini
    style A fill:#90EE90,stroke:#3C883C,stroke-width:2px; %% Hijau muda
    style J fill:#FFB6C1,stroke:#C0392B,stroke-width:2px; %% Merah muda
```