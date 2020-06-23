## Revisions in the Cloud

To make revisions to our work locally and sync with the cloud, 
we use both our *terminals* and *git*.

### What _is_ git?

  Git is a version control system that allows multiple developers to work on the same code. 

  Features of git:  
  -  Saves a history of changes to files  
  -  Allows user to view, apply, and remove changes
  -  Able to keep all project files together

  Git takes snapshots of code in time, where the "commit" function is similar to "save as".  

    Remember that all commits should have a detailed commit message that reminds the user of what changes were made at the time of committal. 


  **HEAD** = the label meaning "You Are Here"

## What is GitHub?

  Github is a way to share code with others, essentially putting your code in **the cloud**. 

    Remember to work on code locally, *then* sync with what is online.

## What are repositories?  

  Repositories are a collection of files the user has told Git to pay attention to.

  -  Usually, one project = one repository
  -  Really large projects might have multiple repositories for different parts of their system
  -  Can live on GitHub *or* the Terminal  
   
    ACP 
      - Add -> git add filename
      - Commit -> git commit -m
      - Push -> git push origin master

    Fix Merge
      - git checkout
    
    Create a File
      - touch filename
    
    Move
      - mv
    
    Change Directory
      - cd