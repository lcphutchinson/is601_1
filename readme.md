# Linux/Git Command Cheat Sheet

This repo is an introductory assignment and exercise in branching and merging. It will contain only this readme, consisting of at least 15 Git or Linux shell commands and their functions, each committed on their own branch.

### Linux Commands

* cd [dir] -- *change directory*: moves the shell frame into a directory at [dir] \(ex. *cd workspace* moves into a directory called workspace inside the working directory\)
* mkdir [path] -- *make directory*: creates a new directory at ./[path]
* mv [file][path] -- *move*: Moves the file at [file] to [path], including renaming the file if [path] specifies a different file name than [file]
* cp [file][path] -- *copy*: Creates a copy of [file] at [path], including renaming the file if [path] specifies a different file name than [file]
* rm [path] -- *remove*: Deletes a single file at [path] if one exists \(or every file in a directory at [path], if the -r option is used\)
* rmdir [path] -- *remove directory*: Deletes a single empty directory at [path], if one exists.
* cat [file] -- *\(?\)*: prints the contents of [file] in the terminal window. \(great for short text files like this one\)
* chmod [file] -- *\(?\)*: Modifies the read/write/execute permissions of [file] \(I constantly had permissions issues when passing files back and forth with University VMs in undergrad. That's how I learned this one.\)

### Git SubCommands

* git status -- displays the tracking status of files in the working branch \(which files' changes are being tracked in the current commit and which aren't, which files are being tracked but have been deleted, etc.\)
* git add [path] -- adds changes from a file at [path] \(or all files in a directory at [path]\) to the current branch. 
* git commit -- saves a commit on the current branch using the current state of staged files.
* git push [remote][branch] -- pushes a ready commit on [branch] to [remote], a remote repository associated with the local project.
* git branch [name] -- creates a new branch labelled [name] with the current staging area \(commonly also used to rename a branch with -m\)
* git checkout [name] -- In its most basic invocation, switches to an existing branch [name] \(I hear it can be used for all sorts of other functions, though\)
* git merge [name] -- applies changes from existing branch [name] onto the current branch \(Assuming no merge conflicts\)

