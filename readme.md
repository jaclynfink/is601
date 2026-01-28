# Linux and Git Command Cheat Sheet

## Linux commands:  
**echo** - print the entered text  
    -n: Do not add a newline character at the end  
    -e: allow escape sequences, meaning do not interpret the given sequence as literal text  
**touch** - create a file  
**wc** - (word count) counts lines, words, and bytes in a specified file  
    -l: prints the number of lines  
    -w: prints the number of words  
    -c: prints the number of bytes  
    -m: prints the number of characters  
**chmod** - (change mode) change permissions on a file  
**chown** - (change owner) change ownership of a file  
**curl** - download or upload data using HTTP, HTTPS, FTP, and more  
**ssh** - connect to a server using Secure Shell protocol  
**awk** - used to split text file into fields and perform pattern searching  
    -F: specify the field separator for the given file  
    -f: read awk program from the given file  
**grep** - searches for regex pattern in text file  
    -c: print the count of matching lines  
    -l: print the file names with matches  
    -i: ignore case  
    -r: recursively search the given directory  
    -v: print lines that do not match  
    -o: print only the matched part of the lines  
**sed** - (stream editor) find, replace, insert, and delete lines in a text file  
**env** - display, create, or update environment variables  
**which** - identify the location of a given executable file  
**cat** - (concatenate) display file contents  
**head -n**  - display the first n lines of a file  
**sort** - print the sorted output of a file  



## Git commands:  
**git status** - displays the current state of the current branch of your working directory  
**git init** - create a new Git repository  
**git diff** - display unstaged changes  
**git add** - stage a new, deleted, or modified file(s)  
**git commit** - save changes made to a file(s) to the local repository  
**git branch** - create, list, rename, or delete a branch  
**git checkout** - switch to a different branch  
**git merge** - combine changes from two branches into one  
**git log** - view the history of commits in a repository  
**git push** - upload local commits into a remote repository  
**git pull** - download changes from a remote repository into your local repository  
**git rebase** - takes changes from one branch and apply them to another branch  
**git stash** - save uncommitted work to a stack for later retrieval if necessary  
**git clone** - download a remote repository to your local machine  
**git config** - retrieve and modify Git configuration values  
