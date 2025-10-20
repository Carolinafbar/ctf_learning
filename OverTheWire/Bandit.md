# OverTheWire Bandit - Learning Notes

This file documents my progress in the **OverTheWire Bandit** wargame, a beginner-friendly introduction to Linux, SSH, and basic cybersecurity concepts.

## Levels Completed
---
### Level 0
**Goal:** Obtain the password for the next level.  
**Commands used:**  
ssh bandit0@bandit.labs.overthewire.org -p 2220  (used to connect to a remote machine securely, -p: Identify the port)
**Password:**bandit0
---
### Level 0 - Level 1
**Goal:** Obtain the password for the next level.  
**Commands used:**  
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls (used to list the contents of a directory)
cat readme (used to show the content of files in the terminal)
---
### Level 1 - 2
**Goal:** Obtain the password for the next level.  
**Commands used:**  
ssh bandit1@bandit.labs.overthewire.org -p 2220
cat - : - is treated as standard input ; use ./- to reference a file literally named -.
cat ./- 
---
### Level 2 - 3
**Goal:** Obtain the password for the next level.  
**Commands used:**  
ssh bandit2@bandit.labs.overthewire.org -p 2220
cat ./--spaces in this filename-- : due to the spaces it looks like I'm trying to look at 4 different files
cat ./"--spaces in this filename--" : using spaces so it recognizes as one file
