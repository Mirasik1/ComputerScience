Software - a program or a set of programs used to manage a computer
Hardware - a common term for the physical parts of the computer, both internal and external.

Application software 
```mermaid
%%{ init { "flowchart": { "curve": "linear" } } }%%
graph TD
    classDef blue fill:#dceefb,stroke:#3b82f6,stroke-width:2px;
    classDef red fill:#fee2e2,stroke:#ef4444,stroke-width:2px;
    
    A[Software] --> B[Application Software]
    A --> C[System Software]
    B --> D[General purpose]
    B --> E[Special Purpose]
    B --> F[Bespoke]
    C --> G[Library programs]
    C --> H[Translators]
    C --> I[Utility programs]
    C --> J[Operating systems]
    H --> K[Assembler]
    H --> L[Compiler]
    H --> M[Interpreter]
    class B,D,E,F blue;
    class C,G,H,I,J,K,L,M red;

```

