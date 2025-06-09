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
  ![image](https://github.com/user-attachments/assets/c60c0e7c-dbcb-4263-ac34-93a1f749d45c)

3. **Searching for Patterns**
   - Used `grep` to find "root" in `/etc/passwd`
![image](https://github.com/user-attachments/assets/80dd8704-22c9-42bd-bc03-c6cd49da4e92)

4. **Zipping and Unzipping**
   - Compressed `test_dir` to `test_dir.zip`
   - Unzipped to `unzipped_dir`
   - ![image](https://github.com/user-attachments/assets/f09cf4a7-8ed2-4f7f-8175-93aeffe78030)


5. **Downloading Files**
   - Used `wget` to download sample file
     ![image](https://github.com/user-attachments/assets/bc312417-b569-4357-9f5e-94f38436a385)


6. **Changing Permissions**
   - Created `secure.txt` and set read-only permissions
     ![image](https://github.com/user-attachments/assets/855f69ef-9c19-4f7c-b050-8373b6a8d911)


7. **Environment Variables**
   - Set `MY_VAR` with value "Hello, Linux!"
![image](https://github.com/user-attachments/assets/c57201fe-7215-4b81-bce1-2ca7b9ca510e)

## Command Reference

```bash
# Sample commands (full commands in documentation)
mkdir test_dir
grep "root" /etc/passwd
export MY_VAR="Hello, Linux!"

