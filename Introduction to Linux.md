# Introduction to Linux - Worksheet

## 1. What is Linux?
- **Definition**: Linux is an open-source operating system kernel.
  - **Open Source**: Source code is freely available for viewing, modification, and distribution.
  - **Kernel**: The core part that manages communication between hardware and software.

## 2. Linux Distributions (Distros)
- **Definition**: Different "flavors" that package Linux with various tools and applications.
- **Examples**: Ubuntu, Fedora, Debian. We will use **Ubuntu**.

## 3. Kernels
- **Definition**: The core component of the operating system.
- **Role**: Facilitates communication between software and hardware.
- **Linux Kernel**: Forms the basis for various Linux distributions.

## 4. Basic Linux Commands
- **Terminal/Shell**: Command-line interface for interacting with the system.
  
### Common Commands:
- `ls`: List files and directories.
- `cd`: Change directory.
- `pwd`: Print the current working directory.
- `mkdir`: Create a directory.
- `touch`: Create an empty file.
- `cp`: Copy files or directories.
- `mv`: Move or rename files or directories.
- `rm`: Remove or delete files or directories.
- `nano` or `vim`: Text editors.
- `cat`: Display the content of a file.
- `man`: Access the manual for a command.

## 5. Using the Terminal

### 5.1 Accessing the Terminal:
- On Linux, find it in the applications menu.
- **Shortcut**: `Ctrl + Alt + T`.

### 5.2 Navigating the File System:
- `pwd` (Print Working Directory): Shows your current location in the file system.
- `ls` (List): Lists files and directories in the current location.
- `cd` (Change Directory): Navigate to a different directory or folder.

### 5.3 File Manipulation:
- `mkdir` (Make Directory): Creates a new directory.
  - **Example**: `mkdir bobmarley`
- `touch`: Creates an empty file.
  - **Example**: `touch newfile.txt`
- `cp` (Copy) and `mv` (Move/Rename): Copies or moves files and directories.
  - **Example**: `cp file.txt backup/`
  - **Example**: `mv old_file.txt new_location/`
  
### 5.4 File Display and Removal:
- `cat`: Displays the content of a file.
  - **Example**: `cat file.txt`
- `rm`: Deletes files or directories.
  - **Example**: `rm unwanted_file.txt`

### 5.5 Getting Help:
- `man` (Manual): Displays the manual for a command.
  - **Example**: `man ls`.

---

## Set of Tasks to Do in the Linux Terminal:

1. **Identify your home folder**: What is the full directory of your home folder? Include any slashes or special characters.
   - ________________________________________

2. **Create a new directory** in your home folder. Name it using the initials of your chavrusa (study partner) group. For example, if Bob Marley and Jack Black were learning partners, the folder would be called `bmjk`. Which command do you use to make new folders?
   - ________________________________________

3. **Navigate into the new folder** you created using the `cd` command. Once you're in the new folder, use the `pwd` command to see your new folder path. What is your new folder path?
   - ________________________________________

4. **Create a file** in the new folder called `deleteme.txt` using `touch`, `nano`, or `vim`. Add some text to the file, then use `cat deleteme.txt`. What is the output of `cat` for your newly made file?
   - ________________________________________________________________________________

5. **Remove the file** using the `rm` command. Afterward, create two new files called `newfile.txt` and `newfile2.txt`. Use the `ls` command to list all the files in your current directory. What output does it show you?
   - ________________________________________________________________________________

6. **Explore the `man` pages** (manual) of the `ls` command. Find out what `ls -lah` does by reading the manual. Explain in your own words what it does.
   - ________________________________________________________________________________

7. **Choose another command** to analyze. Read its man page and find one nuance about the command. Explain it in your own words.
   - ________________________________________________________________________________
