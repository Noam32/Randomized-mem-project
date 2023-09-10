# Randomized-mem-project
Randimized memory access - mitigation against cache timing attacks on embedded hardware (with hardware acclerations on Tensilica Xtensa processors)

Project includes :
2. Randomized memory access accelerator using Tie - hardware project -4th year
(2023):
C,C++and TIE HDL- creating a randomized memory area to protect against timing attacks .
Defining a separate memory region and special registers to be permuted and
shuffled to hide cryptographic secrets.
Creating combinational logic functions and custom assembly instructions.
Separating the "programmers view" of the memory (original address) from the real
address accessed in order to randomize the evictions and cache behavior.
Verifying the correctness and validating the data that was retrieved.
Analyzing the changes in performance (delay,hazards,interlock etc) and the
security gains achieved by our implementation.

![image](https://github.com/Noam32/Randomized-mem-project/assets/104763917/5529855c-6898-4f9a-9da9-302164814dbf)
