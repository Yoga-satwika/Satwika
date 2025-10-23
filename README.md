# Git & GitHub
 Git:- Git is a version control system (VCS) — a tool that helps you track changes in your code over time.
       Git and github allows us to entain the history of the project at a particular point of time, which person made which change where in the project, git helps us in doing that.
       Github is a platform on online website that allows us to host or git repositories.
       
 # Repository
  Understanding what a Git repository is and Initialization of a new repository.
 <img width="932" height="430" alt="git" src="https://github.com/user-attachments/assets/c1f8077f-d7ce-43bb-9f5f-a4ce69e7d718" />
 
 # Committing Changes 
  
   Git add, commit, and commit messages.
   
   <img width="462" height="355" alt="image" src="https://github.com/user-attachments/assets/93531537-1347-4505-a378-aa53dd3b2d69" />



Committing changes to the local repository

<img width="570" height="86" alt="image" src="https://github.com/user-attachments/assets/e2011527-9583-42cc-b990-d1220374587f" />   

# Branching and Merging: 
   Basics of branching and merging in Git.  
   Creating branches for new features or bug fixes.  
       
Remote Repositories:
      A remote repository on GitHub is an online version of your local Git repository.
 Cloning Repositories from Remote Sources 
             Cloning means copying an existing remote repository (from GitHub or elsewhere) to your local computer.
Pushing changes to remote repositories. 
       Pushing means sending your committed changes from your local repository to a remote repository.

Collaborative Work:
       Git and GitHub make it easy for multiple developers to work together on the same project without overwriting each other’s changes.
       
Working with others on the same project.  
       Collaboration means multiple people contribute to the same codebase, each working on their own copy (branch or fork) and later merging their changes into the main project.
       
Handling merge conflicts.  
       A merge conflict occurs when two people edit the same line of code (or file) in different branches, and Git doesn’t know which change to keep.

Git Ignore: 
     Ignoring files and directories using. gitignore.  
         The gitignore files tells git which files or folders to skip tracking - preventing unwanted files from being committed to the repository.

 Tagging: 
       Creating and managing tags for releases or specific points in history.  
              Tagging is used to make a specific commit in git history and helps identify stable versions like v1.0,v2.0
      Two types
          Lightweight tag
              Simple printer to a commit- like a quick label 
           #git tag v1.0
           
Undoing Changes: 
      Reverting commits     
      Resetting changes.
             Undoing changes in git means reverting your repository to a previous state, like discarding, undoing committs or resetting.

 Git Config: 
        Configuration settings for Git, including user information.  
            Git command used to set, view and manage configuration settings for git. It helps you define important details like your username, mail.
 
 Git Hooks: 
      Understanding and utilizing Git hooks for customizing workflows. 
           Git Hooks are scripts that run automatically when certain git events occur-like commit, push, or merge. They helps in automatic checks.

Submodules: 
     Managing and working with submodules within a Git repository.  
           Manage external repositories inside your project.
          Submodules allows you to keep another git repository inside your main repository.

Interactive Rebase: 
      Interactive rebasing for more controlled commit history.  
           Interact rebase is a poweful git command that lets you edit,reorder,combine,or remove committs in your branch.

 Stashing: 
      Temporarily saving changes using git stash.  
           Temporarily save changes without committing so you can switch branches or pull updates without losing your work.

 Git GUIs: 
      Introduction to graphical user interfaces for Git.  
         Git GUI's are graphical user interface that provide a visual way to interact with git repositories.

 Advanced Topics: 
    Topics like reflogs, bisect, and advanced use cases.  
       Git Reflog :- Git reflog is called as reference log. It records every movement of branch tips and head in local repository.
       It helps recover lost committs or to track changes made to the HEAD
Git Commands: 
       Git Clone: Clones a repository into a new directory.  
               
          git clone <repository_url>
Git Add: Adds changes in the working directory to the staging area.  

          git add <file_name>

Git Push: Pushes local changes to a remote repository.  

         git push origin <branch_name>

 Git Pull: Fetches changes from a remote repository and merges them into the current branch.  

     git pull

 Git Fetch: Fetches changes from a remote repository but does not automatically merge them.  

     git fetch

 Git Merge: Merges changes from one branch into another.  

    git merge <branch_name>

 Git Rebase: Combines a sequence of commits into a new base commit.  
    
      git rebase <branch_name>

 Git Revert: Creates a new commit that undoes changes made in a previous commit.  

     git revert <commit_id>

 Git Cherry Pick: Picks a commit from one branch and applies it to another.  

      git cherry-pick <commit_id>

Git Reset: Resets the current branch to a specific commit, optionally preserving changes as uncommitted.  

      git reset --hard <commit_id>

 Git Revert (again): Creates a new commit that undoes changes made in a previous commit. 

         git revert <commit_id>

      

