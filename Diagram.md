flowchart TD
A[User has downloaded the MEMZ trojan] --> B[User runs MEMZ.exe]
B -->|Phase 1| B1[Pop-ups, cursor shaking, random keyboard inputs]
B1 -->|Phase 2| B2[System errors, inverting color display, cursor replacement]
B2 -->|Phase 3| B3[Inverting strings, screen tunneling effect, restarting or attempting to kill the program accelerates the damage]
B3 --> C[Is this MEMZ or MEMZ-Clean?]
C -->|MEMZ-Clean| D[No harm has been done to the system, all the payloads are for entertainment] --> F[MEMZ can be closed]
C -->|MEMZ.exe| E[Catastrophic damage to the system, the payloads are intentional] --> G[Restore the system with a backup]


The process of MEMZ and how it works is highlighted in each box, and the two variants of MEMZ are shown off in the branch as well. While MEMZ-Clean and MEMZ are very similar, the only differences they have are whether or not their payloads are malicious.