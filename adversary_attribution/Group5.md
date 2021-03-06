# Group5
## Description
[[Group/G0043|Group5]] is a threat group with a suspected Iranian nexus, though this attribution is not definite. The group has targeted individuals connected to the Syrian opposition via spearphishing and watering holes, normally using Syrian and Iranian themes. [[Group/G0043|Group5]] has used two commonly available remote access tools (RATs), njRAT and NanoCore, as well as an Android RAT, DroidJack.Citizen Lab Group5
## Attribution
| Tactic | Technique | Tool | Description |
|--------|---------|-------|---------|
| Collection |                   Screen Capture                   |  | Malware used by [[Group5]] is capable of watching the victim's screen.Citizen Lab Group5 |                                         
| Defense Evasion |              File Deletion                    |  | Malware used by [[Group5]] is capable of remotely deleting files from victims.Citizen Lab Group5 |                                 
| Collection Credential Access | Input Capture                    |  | Malware used by [[Group5]] is capable of capturing keystrokes.Citizen Lab Group5 |                                                 
| Command and Control |          Uncommonly Used Port             |  | [[Group5]] C2 servers communicated with malware over TCP 8081, 8282, and 8083.Citizen Lab Group5 |                                 
| Defense Evasion |              Obfuscated Files or Information  |  | [[Group5]] disguised its malicious binaries with several layers of obfuscation, including encrypting the files.Citizen Lab Group5 |
| Defense Evasion |              Software Packing                 |  | [[Group5]] packed an executable by base64 encoding the PE file and breaking it up into numerous lines.Citizen Lab Group5 |         



