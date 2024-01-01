# alphasmart-research
Notes and archives from reverse-engineering Alphasmart Neo binaries

The Ghidra project includes the binaries:
- AlphaWordPlus.os3kapp It is annotated the most thorougly. It implements editing for the one-line input fields, such as name of a file or text to find. However, the logic for the editing the text file as a whole seems to exist in the firmware.
- Calculator.os3kapp, with basic analisys.
- os3kneorom.os3kos, the firmware. 
- NeoManager.exe. The focus is reverse-engineering the protocol of communication with Neo. Curiously, installing an applet and updating firmware have a lot in common.
- Several dlls from the NeoManager that aren't analyzed yet.
