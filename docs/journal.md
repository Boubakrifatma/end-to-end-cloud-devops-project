# Learning Journal

## Day 1 - 30 Sept 2026
**What I did:** Installed Ubuntu 24.04 on VMware, installed Git, connected to GitHub with an SSH key, created the project repo and structure.
**What broke:** 1) apt install failed with "404 Not Found". 2) I was running Ubuntu in live mode (/cow disk full). 3) The installer crashed and the boot froze.
**How I fixed it:** 1) Ran sudo apt update. 2) Understood it wasn't installed (clue: ubuntu@ubuntu and /cow). 3) Created a new clean VM.
**What I learned:** Public vs private SSH keys, always apt update before installing, read error messages for clues, unclosed quotes make the terminal wait with ">".
