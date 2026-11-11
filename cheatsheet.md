# Cheatsheet

## Day 1 – Kali setup(5 Nov 2026) 
- Kali login: username kali, password kali
- cat /etc/os-release: shows which Linux version I'm using?
- If a VM says "Inaccessible", its files are missing. Download the .7z again, extract it and double-click the .vbox file.

  ----------------
  ## Day 02 - 6 November 2026
## Day 2 – Account & Tools Setup ( 6 November 2026) 
1. **TryHackMe** = hands-on hacking practice on safe, pretend machines.
2. **PortSwigger Academy** = free labs for website hacking (SQLi, XSS). Tool: **Burp Suite**.
3. **Pentest steps** = Recon (find info) → Scan → Exploit (break in) → Report.

## Commands 
- `ping <IP>` → check if a machine is online
- `nmap <IP>` → find open ports (doors) on a machine
- `whoami` → shows which user I am

----------------------------
## Day 03 - 7 November 2026 

## GitHub tips
- Type `folder/file.md` when creating a file to make a folder
- Move a file: edit it, then change its path in the name box
- Empty folders don't exist in Git, so add a `.gitkeep` or `README.md`

- -------------------------------
## Day 04 - 8 November 2026

   - `sudo apt update && sudo apt upgrade -y` → update Kali
   - `git add . && git commit -m "msg" && git push` → save work to GitHub
   - VirtualBox: snapshot your VM before big changes so you can roll back
- -------------------------------
## Day 05 - 9 November 2026
## BASIC COMMANDS:
#whoami = which user
#echo= repeat / display the output
# ls 
list all the folders
# cd foldername
go to this folder/ open it 
# cat filename
open a note + read it 
# pwd
where am i ? 

Note : blue = folders & white = files
# find -name file
find a fiel by its name
# grep "word" file
search a word in this file

# &
run this command inn teh background

# &&
run this then that 

# >
overwrite the file content
echo "hello" > notes.txt
# >> 
write the content at the end 

- -------------------------------
## Day 06 - 10 November 2026
**SSH**= ssh username@ip_address
**ls**
list all the files in the directory
**ls -a**
list all the files in the directory + the hidden ones too
**ls -lh**
size+files
**ls --help**
quick cheatsheet
**man ls**
detailed manual

**make a new file**=touch filename
**make a new directory** = mkdir foldername
**copy contents** = cp file1 file2
**move contents** = mv file1 file2
**remove a file**= rm filename
**remove a folder**=rm -R foldername

**settings** = /etc
**administrative control or boss** =/root
**logs**=/var/log
**temporary storage**=/tmp

**in your room** = su user2
**in their room**=su -l user2
**come back to your original room/state**= exit

## Linux Commands part 3 

## Terminal Text Editors

**Open A File to Edit It**= nano filename
**up arrow**= move up
**down arrow**= move down
**enter key**= next line
**save a file**= Control+O
**exit a file**=Control+X
**Search something in the file**=Control+W
*ctrl=^ in linux*

## VIM ( Vi-Improved)
Advanced text editor
**edit** = i 
**exit** = 1. esc key | 2. :q! | 3.enter 

**Pros**
- Customisable: You can change keyboard shortcuts to your liking.
    
- Syntax Highlighting: Shows code in different colours to make it easier to read.
    
- Works Everywhere: Vim works on almost all terminals, even when Nano isn't installed.
    
- Learning Resources: Many cheatsheets and tutorials are available to help you learn Vim.

_______
## Day 07 - 11 November 2026 


## General/Useful Utilities

**Download a file(like clicking a download link)**=wget URL
**Quickly copy a folder** = SCP
*syntax*
scp filename username@  ip-address: location
*to get it back / modicfied version*
scp username@ ip-address: location filename

**enter a remote file manager**= SFTP
*Syntax*
sftp username @ipaddress
*Commands you can use*
|Command|Real-life meaning|
|---|---|
|`ls`|Look at the files in the room|
|`get notes.pdf`|Take a file from their room|
|`put notes.pdf`|Put your file in their room|
|`rename old.txt new.txt`|Rename their file|
|`rm notes.pdf`|Remove a file|
|`exit`|Leave the room|

**turn folder into tiny website**
python3 -m http.server
*port 8000*
_____

## PROCESSES 101
**Running on your terminal** = ps
**running on your terminal + elsewhere** = ps aux
**Live list of programs running** = top 

**PID**= Process id for the running application 

**save before exiting / proper way/ default)** = kill -SIGTERM PID
**forcefully close**= kill -SIGKILL PID
**temporarily pause**=kill - SIGSTOP PID
**temporarily continue**=kill - SIGCONT PID

*NOTE: once a system boots and it initialises, systemd is one of the first processes that are started.*

**SERVICE**: A program that  quietly runs in the background
*syntax*
systemctl [what to do] [which service]
**what to do**



