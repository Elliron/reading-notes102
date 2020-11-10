# Revisions and the Cloud

## Version Control

- Local Version Control
  - One database on  hard disk that stores changes to files
- Centralized Control
  - CVS
  - Single server storing all changes and file versions, can be accessed by multiple people.
  - Helps collaboration, may see others changes
- Distrubuted Version Control
   - DVCS
   - fixes vulnerability of CVS such as server failures and file corruptions
   - allows clients to create mirrored repositories
  
 ## Git
 
 - Snapshots
 
   - DVCS
   - stores data in a file system of snapshots
   - Each save(commit) to a changed version created a snapshot
 - Local Operations
   - Most information found in local resources
   - No need to fetch history information from server
   - Works offline or on VPN
 - Tracking Changes
   - Tracks all changes to file or directory
   - Prevents corruption or information loss
 - Loss of Data
   - Minimizes irreversible damage
 - States
   - committed - stored local database  
   - modified - changed but not committed
   - staged - changed version to be committed to next snapshot
   
  ### History
  
  - Open source software
  - Developers originally used Bitkeeper in 2002 before falling out of use in 2005
  - Created by Linus Torvalds in 2005
  - Most utilized VCS in world
  
  ## Git Commands
  
  ### Check Settings
   - Git config --list
  ### Git Help
   - git help command
   - git command --help
   - man git-command
  ### Setting up Git Repo
   - cd test
   - git init (Creates subdirectory n amed .git)
   - git add *.c (Tracks files)
   - git add LICENSE
   - git commit -em "place message"
     ### Cloning
   - git clone URL (Creates a copy of an existing Git repo)
   - git clone URL mydirectory (Clones into directory)
   
  ### Workflow
   #### Local Repository Structure
    - Working Directory (Files live here)
    - Index (staging)
    - Head (recent commit/save)
   #### Saving Changes
    - Tracked may be modified, unmodified or stage, recent snapshot
    - Untracked not staged or in last snapshot
   #### Life Cycle of File Status
    - Git flags as modified after edit
    - Stage the file
    - Commit staged changes
   #### Check File Status
    - git status (determines file state)
   #### Tracking and Staging New File
    - git add filename (Single)
    - gid add* * (all filles)
   #### Commit File
    - git commit -m "comment on change here"
   #### Commit All
    - git commit -a
   #### Pushing Changes
    - git push origin master
     - pushes from master (local branch) to origin(remote repository)
   #### Stashing Changes
    - git stash (temp removes and hides changes)
    -git stash apply (retrieve hidden changes)
   #### Remote Repositories
    - Allows collaboration on projects
    - Read/Write or Read-only privileges
   #### Cloned Repositories
    - Auto name = "origin"
    - Auto name = "master" for local
    
   [More information on Git](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#2_4)
   
    
    
[<==Back](README.md)
