# Analysis and Comparison of WannaCry and NotPetya

In this paper you can find thorough analysis of two malware - WannaCry and NotPetya. The analysis was split in two main phases (Basic and Advanced analysis) and their respective subparts (Static and Dynamic analysis).

The basic analysis aimed to obtain information about them and how they function with the use of multiple tools. Floss and PEStudio were used in the basic analysis to extract data (imported libraries, strings, functions) from the hostile programs without executing them. Subsequently, the analyst executed the malware to inspect the detonation symptoms and then monitored them with the use of network and host-based tools – TCPView, Wireshark and Procmon.

Afterwards, the analysis moved on to the second phase – the Advanced analysis. A disassembler (Ghidra) was used to reverse engineer the samples. The code revealed a lot of information about how the hostile software implemented the imported blacklisted libraries and their functions. A debugger (x32dbg) aided with altering the workflow of the samples by bypassing the killswitches and executing the sample (WannaCry). 

In the end the samples were compared and appropriate pre- and post-infection countermeasures were provided.

References of used material and libraries were provided as requested from the academic staff.
