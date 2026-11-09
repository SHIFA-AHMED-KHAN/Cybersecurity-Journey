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
# grey "word" file
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
