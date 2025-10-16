 Repository: 
       Repository means a storage place where all your project files and their change history are saved and managed.
1.1 Understanding what a Git repository is.  
      A Git repository is a version-controlled folder.
      version - controlled folders is a normal folder where Git keeps track of every change you make to the files — like saving all versions so you can go back anytime.
      
   It contains:
      
 Files and folders of your project.
      Commit history (all previous versions of your files).
      Branches (different development lines).
      Types of repositories:
      Local repository – exists on your own computer.
      Remote repository – exists on a server (like GitHub, GitLab, or Bitbucket) to share with others.

1.2 Initialization of a new repository.  
    Step 1: Open the Terminal or Command Prompt
            On Windows: You can use Git Bash or Command Prompt.
            On Mac/Linux: Use the built-in Terminal.
  
   Step 2: Navigate to Your Project Folder
Use the cd command (which means change directory) to go inside the folder you want to track.
Example:
<img width="457" height="244" alt="image" src="https://github.com/user-attachments/assets/38756bec-a84d-4c6d-bd3b-8af9bfc1ebd6" />

     cd path/to/your/project
  If your project folder is named myproject and is on the desktop:
<img width="457" height="244" alt="image" src="https://github.com/user-attachments/assets/7a704147-bf09-4bdf-abb9-ab866c806f22" />

     cd Desktop/myproject
  Step 3: Initialize Git

  Run the following command
<img width="457" height="244" alt="image" src="https://github.com/user-attachments/assets/af0729bc-c3e0-4b6b-a6bf-b07543988dc3" />

  Git creates a hidden folder named .git inside your project.

This .git folder stores:
All version history
Configuration files
Branch information
Commit data
Step 4: Check the Repository Status
You can check the current state of your repository by running:

  

  





