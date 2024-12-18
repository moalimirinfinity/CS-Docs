## **1. Basic Navigation**

| **Command** | **Description** | **Example with Suffix** |
| --- | --- | --- |
| `pwd` | Show the current directory. | `pwd` → `/Users/username` (No common suffix for this command) |
| `ls` | List files in the directory. | `ls -l` → Detailed list with permissions and file info |
|  |  | `ls -a` → Include hidden files |
|  |  | `ls -lh` → Human-readable file sizes |
| `cd` | Change directory. | `cd ~` → Go to home directory |
|  |  | `cd ..` → Move up one directory |
|  |  | `cd /path/to/folder` → Absolute path |
| `mkdir` | Create a new directory. | `mkdir -p new/folder` → Create parent directories if they don’t exist |
| `touch` | Create an empty file. | `touch file.txt` → Creates file |
|  |  | `touch -t 202401010000 file.txt` → Set file timestamp to Jan 1, 2024 |

## **2. File Operations**

| **Command** | **Description** | **Example with Suffix/Option** |
| --- | --- | --- |
| `cp` | Copy files or directories. | `cp -r folder1 folder2` → Recursively copy folder1 and its contents to folder2 |
|  |  | `cp -i file1.txt file2.txt` → Prompt before overwriting file2.txt |
|  |  | `cp -v file1.txt file2.txt` → Show files as they are being copied |
| `mv` | Move or rename files. | `mv -i file1.txt new_folder/` → Prompt before overwriting files in destination |
|  |  | `mv -v file1.txt new_folder/` → Show files as they are being moved |
| `rm` | Remove files or directories. | `rm -i file.txt` → Prompt before deleting |
|  |  | `rm -r folder` → Recursively remove a folder and its contents |
|  |  | `rm -f file.txt` → Force delete without prompt |
| `cat` | Display file contents. | `cat file.txt` → Show contents of the file |
|  |  | `cat file1.txt file2.txt` → Concatenate and display files |
|  |  | `cat -n file.txt` → Number lines of the file output |
| `nano` | Edit files in a simple text editor. | `nano file.txt` → Open file for editing |
|  |  | `nano +15 file.txt` → Open file at line 15 |
| `head` | Show the beginning of a file. | `head -n 10 file.txt` → Show first 10 lines of a file |
| `tail` | Show the end of a file. | `tail -n 10 file.txt` → Show last 10 lines of a file |
|  |  | `tail -f log.txt` → Continuously display the last lines as a file updates |

## **3. File Permissions**

| **Command** | **Description** | **Example** |
| --- | --- | --- |
| `chmod` | Change file permissions. | `chmod 755 script.sh` |
| `chown` | Change file ownership. | `chown user file.txt` |
| `ls -l` | View file permissions. | `ls -l` → `-rw-r--r--` |

## **4. Process Management**

| **Command** | **Description** | **Example** |
| --- | --- | --- |
| `ps` | List running processes. | `ps aux` |
| `top` | Display active processes. | `top` |
| `kill` | Kill a process by PID. | `kill 12345` |
| `bg` | Resume process in background. | `bg` (after `Ctrl+Z`) |
| `fg` | Resume process in foreground. | `fg` (after `Ctrl+Z`) |

## **5. Advanced File Operations**

| **Command** | **Description** | **Example** |
| --- | --- | --- |
| `find` | Search for files. | `find . -name "file.txt"` |
| `grep` | Search within files. | `grep "search_term" file.txt` |
| `tar` | Archive files. | `tar -cvf archive.tar folder/` |
| `zip` | Compress files. | `zip file.zip file1.txt file2.txt` |
| `rsync` | Sync files/directories. | `rsync -av folder1/ folder2/` |

## **6. Networking**

| **Command** | **Description** | **Example** |
| --- | --- | --- |
| `ping` | Test network connectivity. | `ping google.com` |
| `ssh` | Connect to a remote server. | `ssh user@hostname` |
| `scp` | Copy files to/from a remote host. | `scp file.txt user@host:/path/` |
| `curl` | Download data from a URL. | `curl -O https://example.com/file` |
| `wget` | Download files from the web. | `wget https://example.com/file` |

## **7. System Monitoring**

| **Command** | **Description** | **Example** |
| --- | --- | --- |
| `df` | Check disk space usage. | `df -h` |
| `du` | Check directory space usage. | `du -sh Documents/` |
| `free` | Display memory usage. | `vm_stat` |
| `top` | Monitor system performance. | `top` |

## **8. Shell Scripting**

| **Command** | **Description** | **Example** |
| --- | --- | --- |
| `echo` | Display a message. | `echo "Hello, World!"` |
| `>` | Redirect output to a file. | `echo "data" > file.txt` |
| `>>` | Append output to a file. | `echo "more data" >> file.txt` |
| ` | ` | Pipe output to another cmd. |
| `bash` | Execute a script. | `bash script.sh` |

## **9. Customization and Utilities**

| **Command** | **Description** | **Example** |
| --- | --- | --- |
| `alias` | Create command shortcuts. | `alias ll="ls -l"` |
| `crontab` | Schedule tasks. | `crontab -e` |
| `brew` | Install software with Homebrew. | `brew install python` |
| `man` | Display manual pages for commands. | `man ls` |
