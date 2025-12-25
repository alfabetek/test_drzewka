```mermaid
graph LR

%% ===== STYLE KOLORÓW =====
classDef club fill:#ffffff,stroke:#000000,color:#000000,stroke-width:2px;
classDef spade fill:#ffffff,stroke:#000000,color:#000000,stroke-width:2px;
classDef diamond fill:#ffe6e6,stroke:#cc0000,color:#990000,stroke-width:2px;
classDef heart fill:#ffe6e6,stroke:#cc0000,color:#990000,stroke-width:2px;
classDef nt fill:#e3f2fd,stroke:#1565c0,color:#0d47a1,stroke-width:2px;

%% ===== OTWARCIE =====
A[1BA<br/>(15–17)]:::nt

%% ===== ODPOWIEDZI =====
A --> B1[2♣<br/>Stayman]:::club
A --> B2[2♦<br/>transfer ♥]:::diamond
A --> B3[2♥<br/>transfer ♠]:::heart
A --> B4[2♠<br/>minor / invit]:::spade
A --> B5[2BA<br/>invite]:::nt
A --> B6[3BA]:::nt
A --> B7[3♣<br/>minor]:::club
A --> B8[3♦<br/>minor]:::diamond

%% ===== STAYMAN =====
B1 --> C11[2♦<br/>brak czwórek]:::diamond
B1 --> C12[2♥<br/>4♥]:::heart
B1 --> C13[2♠<br/>4♠]:::spade

%% ===== TRANSFER ♥ =====
B2 --> D21[2♥<br/>accept]:::heart
D21 --> D22[2BA<br/>invite]:::nt
D21 --> D23[3♥<br/>GF]:::heart
D21 --> D24[4♥]:::heart

%% ===== TRANSFER ♠ =====
B3 --> E31[2♠<br/>accept]:::spade
E31 --> E32[2BA<br/>invite]:::nt
E31 --> E33[3♠<br/>GF]:::spade
E31 --> E34[4♠]:::spade

%% ===== 2♠ PO 1BA =====
B4 --> F41[3♣]:::club
B4 --> F42[3♦]:::diamond

%% ===== ZAPROSZENIA =====
B5 --> G51[3BA]:::nt
B5 --> G52[4♥]:::heart
B5 --> G53[4♠]:::spade
```

