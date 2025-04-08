Software - a program or a set of programs used to manage a computer
Hardware - a common term for the physical parts of the computer, both internal and external.

Application software 
```mermaid
%%{ init: { "flowchart": { "curve": "linear" } } }%%
graph TD
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
    class A base;
    class B,D,E,F blue;
    class C,G,I,J,H red;
    class K,L,M purple;

```

[[Application Software]]
[[System Software]]
[[General]]
[[Special]]
[[Bespoke]]
[[Library ]]
[[Translators]]
[[Utility]]
[[Operating Systems]]