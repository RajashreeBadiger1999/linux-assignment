1. What is the difference between mkdir and touch?
   mkdir: create directory or folder 
       command: mkdir <dir name>
   touch: to create file  
       command: touch <file_name with extention>

2. What is the difference between cp and mv?
   cp: copy 
    used to copy content from one file to another file 
    command: cp <file1> <file2>
             cp <file1> <directory_path>

    mv: move / cut paste
    used to move file from one directory to another directory (also used to rename the file) 
    command: mv <file_name> <directory_name>
             mv <old_file_name> <new_file_name>


3. What happens when you use cat > file.txt and the file already exists?
   cat > file.txt : overwrites the file content.


4. What happens when you use cat >> file.txt and the file already exists?
   cat >> file.txt : it will append new content to the existing content.


5. What does Ctrl+D do when using cat > file.txt?
   Ctrl+D: finished entering the input to file.txt


6. What is the difference between cat and tac?
   cat: used to view/display file content
   cat > file_name: used to overwrite the existing file content.  
   cat >> file_name: used to append new content to the existing file content.


  tac: used to display the file content in reverse order
  ex: file content is
      line 1
      line 2
      line 3

     command: tac file_name
     it will disply
     line 3
     line 2
     line 1


7. What is the purpose of head?
   head: used to fetch/display the first 10 lines of a file by default.
      command: head <filename>

8. What is the purpose of tail?
   tail: used to fetch/display the last 10 lines of a file.
      comamnd: tail <filename>
      if we want to fetch only 5 line [command: tail -n 5 <filename>]


9. How do you display only the first 5 lines of a file?
   head -n 5 <file_name>

10. How do you display only the last 5 lines of a file?
    tail -n 5 <file_name>

11. What happens if you use mv to move a file to another directory? 
    used to  move the file from one directory to another directory, removed from the original directory and placed in the destination directory

12. Can cp copy a directory? If yes, what option is generally required?
    yes we can copy directory, but recursive option is required
    command: cp -r <dir1> <dir2>  


13. where do you find system log files? which directory?
    system logs are generally stored in the var/log directory. 
