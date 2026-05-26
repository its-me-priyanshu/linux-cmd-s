File management in Linux
File and Directory Management
Lists files and directories in the current location.
 "ls"
Changes the working directory.
 "cd /path/to/directory "
Prints the current working directory.
  "pwd"
Creates a new directory.
   "mkdir new_folder"
Removes an empty directory.
   "rmdir empty_folder"
Deletes a file.
   "rm file.txt"
Deletes a folder and its contents.
  "rm -r folder"
 Copies a file.
    "cp file1.txt file2.txt"
Copies a directory recursively.
    "cp -r dir1 dir2 "
Moves or renames a file or directory.
  "mv old_name new_name"
  
File Viewing and Editing

Displays file content.
  "cat file.txt"
 Displays file content in reverse order.
   "tac file.txt"
Opens a file for viewing with scrolling support.
  "less file.txt"
Similar to less, but only moves forward.
   "more file.txt"
Displays the first 10 lines of a file.
  "head -n 10 file.txt"    # -n 10 (No. of lines) # head (Starting lines)
Displays the last 10 lines of a file.
   "tail -n 10 file.txt"    # tail (last lines)
Opens a simple text editor.
    "nano file.txt"         # nano is a file editor
Opens a powerful text editor.
   "vi file.txt"            # vi is a file editor 
Writes text to a file, overwriting existing content.
    "echo 'Hello' > file.txt"
Appends text to a file without overwriting.
    "echo 'Hello' >> file.txt"
