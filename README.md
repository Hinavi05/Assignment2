### 1.Create a repository named as “Assignment 2” in github with Readme.md file,Questions must be paste in the readme file.
    https://github.com/Hinavi05/Assignment2.git
    
### 2.Clone your repository.

    $ git clone https://github.com/Hinavi05/Assignment2.git
    Cloning into 'Assignment2'...
    remote: Enumerating objects: 6, done.
    remote: Counting objects: 100% (6/6), done.
    remote: Compressing objects: 100% (3/3), done.
    remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
    Receiving objects: 100% (6/6), done.
    
 ### 3.Add the text file that should have the answer of Q1.

    $ git add Q1.txt

### 4.Add another file to do the following.

    $ touch anotherfile.txt

### 5.Create another branch

    $ git checkout -b anotherBranch
    Switched to a new branch 'anotherBranch'

### 6.Make changes to your files

### 7.see if the file change is detected with git status.

    $ git status
    On branch anotherBranch

    No commits yet

    Changes to be committed:
      (use "git rm --cached <file>..." to unstage)
            new file:   Q1.txt
            
    Untracked files:
    (use "git add <file>..." to include in what will be committed)
        Assignment2/
        anotherfile.txt

### 8.stage the changes with git add .

    $ git add .
    
### 9.check that the add did what you expected with git status.

    $ git status
    On branch anotherBranch

    No commits yet

    Changes to be committed:
      (use "git rm --cached <file>..." to unstage)
            new file:   Assignment2
            new file:   Q1.txt
            new file:   anotherfile.txt

### 10.make the commit with git commit.

### 11. Write a meaningful commit message (e.g. "Answers question 1").

    $ git commit -am "Answer Question"
    [anotherBranch (root-commit) 82589e4] Answer Question
     3 files changed, 2 insertions(+)
     create mode 160000 Assignment2
     create mode 100644 Q1.txt
     create mode 100644 anotherfile.txt

### 12. check that your working directory is clean with git status.

    $ git status
    On branch anotherBranch
    nothing to commit, working tree clean

### 13. check that your commit succeeded as expected with git log

    $ git log
    commit 82589e478274bead20e29b829d220b9d2e3379c9 (HEAD -> anotherBranch)
    Author: shanthika <sriyanthishanthika@gmail.com>
    Date:   Sun Sep 12 02:54:11 2021 +0530

        Answer Question

 ### 14. Push your code up to a github repository.
 
    $ git push origin anotherBranch

    Enumerating objects: 4, done.
    Counting objects: 100% (4/4), done.
    Delta compression using up to 4 threads
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (4/4), 354 bytes | 354.00 KiB/s, done.
    Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
    remote:
    remote: Create a pull request for 'anotherBranch' on GitHub by visiting:
    remote:      https://github.com/Hinavi05/Assignment2/pull/new/anotherBranch
    remote:
    To https://github.com/Hinavi05/Assignment2.git
     * [new branch]      anotherBranch -> anotherBranch

    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
