# Git_basic
Learning how to use git ,the various commands in git how to use then and when.

1)To check version: git --version

2)To clear terminal: clear

3)Configuring Git:

  git config --global user.name"name used to login in github(recommended)"

  git config --global user.email"mail used to login in github(recommended)"
  
  git config --list

4)Clone & Status:(these cmd are used in local machine like VScode etc)
  
*)Clone-cloning a repository on our local machine.
  
  git clone<link(code link from the repo which we are working in github mainly https)>
  
*)Status-display the state of the code.
  
  git status
  
  There are 4 types of status:
  
  1)untracked-new files that git doesn't yet track
  
  2)modified-changed file
  
  3)staged-file is ready to committed
  
  4)unmodified-unchanged

5)Change directory: cd filename(could use tab for autocompletion)

6)List files: 
  
  ls (but it doesn't show hidden files)
  
  ls -a(used to show all files including hidden ones)
              
7)Whatever change we make to the clone in VScode will only appear on github repo only if we commit it otherwise a symbol M will be appearing at end of file when we save the change in VScode and if we run git staus it will show eg,modified:  README.md 
After modifying a file we have to follow 2step process:

1)add

2)commit

unless we do this status will show error
