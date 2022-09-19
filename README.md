STILL IN PROGRESS - NOT FINAL
# The Ultimate Guide to Git
The purpose of this guide is not to give you a "cheat sheet" to Git commands, but to get you familiar with how it works on a fundamental level. We'll first cover what a version control system is and why you should you use it. We'll then move on to how Git specifically works, and then we'll get familiar with some git commands and what exactly they do. 

## What is a Version Control System?
A version control system (vcs) is a system that saves "snapshots" of your current directory, allows you to view the changes that you've previously made, and rollback versions of your code. Here's a very simple example of a use case: Imagine you're working on file A, you write some code, decide you've done enough work for today, and close your laptop. The next day you come back and write some more code, then realize that the previous version of your code was better. Now, if you had commited the work you had done yesterday to a vcs, then you could just checkout to your previous commit. Without a vcs, you're stuck hoping that you didn't make too many edits to your code so that control-z still works. While, you could technically do control-z for a small project like this, the beauty of a vcs is that it can scale up to projects of a massive size and still run reliably. It doesn't matter if you have 1 file with 10 lines of code, or 2,000 files with 20k+ lines of code - you'll still have a record of all versions of your code. 

## What is Git
Git is one of the most popular free and open-source version control systems out there. It's was originally created by Linus Torvalds (who also created the Linux os) on April 7, 2005

## How does Git Work?

### Git's File Structure
Whenever you create a git repository with ```git init```, Git creates a hidden folder called ```.git/```. The dot suffix tells your computer to hide the folder. Inside this folder you will see the following folder structure:

.git/  
├── hooks/  
├── info/  
├── logs/  
    ├── refs/  
    ├── heads/  
    ├── remotes/  
        ├── origin/  
        ├── .../  
        └── HEAD  
    ├── objects/  
        ├── 00/  
            ├── 0f33j4nenvi34857313840583731b7oh7  
            └──...  
        ├── 0a/  
        ├── 0b/  
        └──.../  
    ├── refs/  
        ├── heads/  
        ├── main  
        ├── remotes/  
            ├── origin/  
            └── skeleton/  
        └──tags/  
    ├── COMMIT_EDITMSG  
├── config  
├── description  
├── FETCH_HEAD  
├── HEAD  
├── index  
├── Main.java  
└── ORIG_HEAD  
  
  Depending on what you've done so far with your project, your git directory may or may not have some of the folders above. 
  
  ### Blobs, Trees, and Commits
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
