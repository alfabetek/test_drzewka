graph LR

%% ===== DEFINICJE STYLI =====
classDef club fill:#ffffff,stroke:#000000,color:#000000,stroke-width:2px;
classDef spade fill:#ffffff,stroke:#000000,color:#000000,stroke-width:2px;
classDef diamond fill:#ffe6e6,stroke:#cc0000,color:#990000,stroke-width:2px;
classDef heart fill:#ffe6e6,stroke:#cc0000,color:#990000,stroke-width:2px;
classDef nt fill:#e3f2fd,stroke:#1565c0,color:#0d47a1,stroke-width:2px;

%% ===== DRZEWKO =====
A[1BA]:::nt --> B1[1♣]:::club
A --> B2[1♦]:::diamond
A --> B3[1♥]:::heart
A --> B4[1♠]:::spade
A --> B5[1NT]:::nt
