# linux-command-tasks
# Linux Command Line Tasks

This repository documents my practice with basic Linux commands.

## Tasks Completed

1. **Creating and Renaming Files/Directories**
   - Created `test_dir` directory
   - Created `example.txt` file inside it
   - Renamed to `renamed_example.txt`
     ![image](https://github.com/user-attachments/assets/b083dbc8-91af-4f20-935f-1ce32c6b648f)
     
2. **Viewing File Contents**
   - Displayed `/etc/passwd` contents
   - Showed first 5 lines with `head`
   - Showed last 5 lines with `tail`
 ![image](https://github.com/user-attachments/assets/ed2c51f4-acbc-4a72-9ca0-09f414853e87)

3. **Searching for Patterns**
   - Used `grep` to find "root" in `/etc/passwd`

4. **Zipping and Unzipping**
   - Compressed `test_dir` to `test_dir.zip`
   - Unzipped to `unzipped_dir`

5. **Downloading Files**
   - Used `wget` to download sample file

6. **Changing Permissions**
   - Created `secure.txt` and set read-only permissions

7. **Environment Variables**
   - Set `MY_VAR` with value "Hello, Linux!"

## Command Reference

```bash
# Sample commands (full commands in documentation)
mkdir test_dir
grep "root" /etc/passwd
export MY_VAR="Hello, Linux!"

