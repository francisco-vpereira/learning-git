# 1.
  - Create repository on github website. 
  - Add markdown file ( README.md ) 
  - Switch to texteditor ( VSCode )
  - Open new folder or existing one 
  - Open terminal : View > Terminal 
  - To clone repository from github to our local machine type the following command : git clone <\HTML link> | git clone <\SSH key>
  - Whenever we make a modification the command <git status>  will always return a message telling us what files have been modified.
  - If we create a new file and run the command <git status> we'll see a message refering to untracked files. That means that git doesn't know what those files are. 
  - In order to track the file we need to run the following command <git add -name_of_the_file> or <git add .>. The latter will track all the files in the list of untracked files and modified files. When all the files are tracked we can commit them. 
  - After this we need to run the following command <git commit -m "message1" -m "message2">. At this point the changes are only available on our local machine and not on github. 

# 2.
