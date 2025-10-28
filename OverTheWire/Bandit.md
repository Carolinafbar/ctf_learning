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

---
### Level 3 - 4
**Goal:** Obtain the password for the next level.  
**Commands used:**  
ssh bandit3@bandit.labs.overthewire.org -p 2220
ls
cd ./inhere
find
cat ./...Hiding-From-You

---
### Level 4 - 5
**Goal:** Obtain the password for the next level.  
**Commands used:**  
ssh bandit4@bandit.labs.overthewire.org -p 2220
ls
cd ./inhere
file ./* (*=todos)
cat ./-file07

---
### Level 5 - 6
**Goal:** Obtain the password for the next level.  
**Commands used:**  
ssh bandit5@bandit.labs.overthewire.org -p 2220
ls
cd ./inhere
du -b -a | grep 1033
cat 

---
### Level 5 - 6
**Goal:** Obtain the password for the next level.  
**Commands used:**  
ssh bandit5@bandit.labs.overthewire.org -p 2220
ls
cd ./inhere
du -b -a | grep 1033 (du → mostra o uso de disco (disk usage) de arquivos e diretórios.-b → mostra o tamanho em bytes.a → inclui arquivos individuais (não apenas diretórios) no resultado.| grep 1033 → filtra a saída do du, mostrando apenas as linhas que contêm “1033”.)

cat ./maybehere07/.file2
---
### Level 6 - 7
**Goal:** Obtain the password for the next level.  
**Commands used:**  
ssh bandit6@bandit.labs.overthewire.org -p 2220
find / -type f -user bandit7 -group bandit6 -size 33c (permission denied)
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null (esconde so resultados de erro)
cat /var/lib/dpkg/ibnfo/bandit7.password

---
### Level 7 - 8
**Goal:** Obtain the password for the next level.  
**Commands used:**  
ssh bandit7@bandit.labs.overthewire.org -p 2220
grep 'millionth' data.txt

---
### Level 8 - 9
**Goal:** Obtain the password for the next level.  
**Commands used:**  
ssh bandit8@bandit.labs.overthewire.org -p 2220

