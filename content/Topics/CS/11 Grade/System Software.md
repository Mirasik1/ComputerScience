-designed to operate the computer hardware and to provide a platform for running application software.

```mermaid
%%{ init: { "flowchart": { "curve": "linear" } } }%%
graph TD
	C[System Software]
	C --> G[Library programs]
    C --> H[Translators]
    C --> I[Utility programs]
    C --> J[Operating systems]

```
## Library programs
---
- are collections of pre-written code, functions, or routines that programmers can use to perform common tasks
- (Example: PIL / Random / Keras )
---
## Translators
---
-  translate high-level language programs into machine language programs that the central processing unit (CPU) can understand.
```mermaid
%%{ init: { "flowchart": { "curve": "linear" } } }%%
graph TD
	H[Translators]
	H --> K[Assembler]
    H --> L[Interpreter]
    H --> M[Compiler]
```
- (Example: Assembler / Interpreter / Compiler)
### Assembler
- converts **assembly language** code into **machine code**
### [[Compiler VS Interpreter]]
---
## Utility programs
- designed to help manage, maintain, and optimize a computer's performance. They perform specific tasks such as file management, antivirus scanning, disk cleanup, and system backups.
- (Example: antivirus, File Management System, Compression tools, Disk Cleanup tool)
---
## [[Operating Systems]]
