---
---

--- Before Day-1 ---  
I already knew basic Python programming, Git fundamentals, and how to use VS Code.   
I had some experience with Linux commands such as cd, ls, mkdir, and file navigation.  

--- 

## Day-1 Checklist

- [x] I can open a Linux terminal and recognize the shell prompt (`user@machine:~$`)
- [x] I can run `python --version`, `git --version`, and `uv --version` without errors
- [x] I can open VS Code connected to WSL/Linux using `code .`
- [x] I know what `~` means and can navigate to my home directory using `cd ~`
- [x] I can create folders and files using `mkdir` and `touch`, and list them with `ls`
- [x] I know the difference between `.xyz`, `./xyz`, and `../xyz`
- [x] I know that in Linux, everything is a file
- [x] I can navigate to the C and D drives within WSL
- [x] I understand the difference between `>` (overwrite) and `>>` (append)
- [x] I have a GitHub account and have created the `tds-bootcamp` repository

--- After Day-1 ---  
I learned how WSL integrates Linux with Windows, how to use the `uv` package manager, and how GitHub repositories are used throughout the bootcamp.   
I also became more comfortable navigating the Linux filesystem and using terminal commands for file management.  

---

--- Feedback (Suggestions for the TDS Team) ---  
The setup instructions were clear and easy to follow. A short troubleshooting guide for common WSL, Git, and VS Code issues could help beginners complete the setup faster.  

---

---

## Notes for Future Reference

### Basic Navigation
pwd             # Show current directory
ls              # List files and folders
ls -la          # List all files including hidden files
cd ~            # Go to home directory
cd ..           # Move one directory up
cd <folder>     # Enter a folder

### File and Directory Operations
mkdir myfolder  # Create a directory
touch file.txt  # Create an empty file
cp a.txt b.txt  # Copy a file
mv a.txt b.txt  # Rename or move a file
rm file.txt     # Delete a file
rm -r folder    # Delete a directory

### Viewing File Contents
cat file.txt    # Display file contents
head file.txt   # Show first few lines
tail file.txt   # Show last few lines

### Output Redirection
echo "Hello" > file.txt   # Overwrite file
echo "World" >> file.txt  # Append to file

### Useful Paths
~       -> Home directory
.       -> Current directory
..      -> Parent directory
./file  -> File in current directory
../file -> File in parent directory

### Version Checks
python --version
git --version
uv --version

### Git Commands
git clone <repo-url>
git status
git add .
git commit -m "message"
git push origin main

### WSL Drive Locations
cd /mnt/c   # C drive
cd /mnt/d   # D drive

### VS Code
code .      # Open current folder in VS Code

### Helpful Shortcuts
Ctrl + C    # Stop current command
Ctrl + L    # Clear terminal
Tab         # Auto-complete names
↑ / ↓       # Command history

---
