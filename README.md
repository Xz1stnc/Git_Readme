# My cheat sheet for git

----

## **Bash commands**

----

1. **cd** __*directory name*__ - move to selected directory.
2. **ls** __*-a*__ - write a file list in working directory.
3. **touch** __*filename*__ - create a new file in working directory.
4. **mkdir** __*directory_name*__ - create a new directory in working directory.
5. **cp** __*target_name*__ __*directory_name*__ - copy target file to target directory.
6. **mv** __*target_name*__ __*directory_name*__ - move target file to target directory.
7. **cat** __*target_file*__ - read any target text file, return echo in terminal.
8. **rm** __*target_file*__ - remove target file from working directory.
9. **rmdir** __*dir_name*__ - remove empty dir.
10. **rm** __*-r*__ __*target_dir*__ - remove dir and all inclusive files (recursive).
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
10. **git** __add__ __filename__ - add one file to tracked.
11. **git** __*add ./directoryname*__ - add directory to tracked.
12. **git** __*commit*__ __*-m*__ - create commit with text message.