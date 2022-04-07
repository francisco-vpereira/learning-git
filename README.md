# 1. Starting a repository on github website and clone it into our machine

  - Create repository on github website. 
  - Add markdown file : README.md. 
  - Switch to texteditor ( VSCode )
  - Open new folder or existing one 
  - Open terminal : View > Terminal 
  - To clone repository from github to our local machine type the following command : ***git clone < HTML link>*** or ***git clone < SSH key>***
  - Whenever we make a modification on a file the command ***git status***  will always return a message telling us what files have been modified.
  - If we create a new file and run the command ***git status*** we'll see a message refering to untracked files. That means that git doesn't know what those files are. 
  - In order to track the file we need to run the following command ***git add -name_of_the_file*** or ***git add .***
  - The latter will track all the files in the list of untracked files and modified files. When all the files are tracked we can commit them. 
  - After this we need to run the following command ***git commit -m "message1" -m "message2"***. At this point the changes are only available on our local machine and not on github. 
  - In order to sincronize our local code with our github website code we need to use the command ***git push origin main***. However in order to do this we need to generate an SSH key and add it to our github account ( see  [1](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) and [2](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)). At this point, if we refresh our github page we'll see the changes that we've made in our texteditor. 
  - Now let's say that we have made changes to some of our files in our github page. In order to update the files in our local machine we must execute the following command ***git pull*** on the VSCode terminal.

# 2. Starting a repository in our local machine and upload it to our github account

-blabla
- sdfadsfag
