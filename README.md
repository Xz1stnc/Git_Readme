# My cheat sheet for git

----

## **Bash commands**

----

1. **cd** __*directory name*__ - move to selected directory.
2. **ls** __-a__ - write a file list in working directory.
3. **touch** __filename__ - create a new file in working directory.
4. **mkdir** __directory_name__ - create a new directory in working directory.
5. **cp** __target_name__ __directory_name__ - copy target file to target directory.
6. **mv** __target_name__ __directory_name__ - move target file to target directory.
7. **cat** __target_file__ - read any target text file, return echo in terminal.
8. **rm** __target_file__ - remove target file from working directory.
9. **rmdir** __dir_name__ - remove empty dir.
10. **rm** __-r__ __target_dir__ - remove dir and all inclusive files (recursive).
11. **&&** - fuse commands (touch text.txt&&cat text.txt).

----

## **Git Bash**
1. **git version** - print version of installed git.
2. **git config** --global - config you git.
3. **git config --global user.email** __usermail__ - visible email.
4. **git config --global user.name** __username__ - visible nickname.
5. **cat ~/.gitconfig** or **git config --list** - print your config file in terminal.
6. **git init** - create a local repository in current working directory.
7. **rm -rf .git** - remove a local repository in current working directory.
8. **git status** - status of your repository.
9. **git add --all** - add all files in directory to repository (__in tracked status__).
10.**git** __add__ __filename__ - add one file to tracked.