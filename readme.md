1. vi commands = i: insert mode (for editing), esc: end editing/open menu,
    1a. vi menu commands - :w - write (save), :wq - write-quit, :q - quit
2. git init = initialize directory #note# to initialize new repo with 'main' as default, must use git init -b main
3. git status = show non-commited changes to repo
4. git commit = 'saves' changes. Records changes to repo. Tracks all historical changes so an accurate view of the project may be generated for any point in time.
    4a. git commit -a = auto stages modified files to be committed 
    4b. git commit -am 'message' = auto stages and adds message
5. git checkout -b new-branch  = creates a new branch off of main/master. used for team collab, de-risk altering main/master
6. git merge --ff-only <branch> = merges branch changes to main/master. ff merge only avaialbe if main/master is has no new commits after <branch> is created. ff creates a more linear workflow, easier to view history
7. git pull origin branch = copies/merges updates from the specified branch to a different branch. ensures you work from the current project and may make changes in paralell

linux commands
8. ls = lists contents of a directory
    ls -a = lists all files
    ls -l = provides list with file details
9. mkdir [directory name] = make directory
10. cd [directory name] = change directory
11. touch [filename] = create a new file
12. rm [filename] = deletes a file
    rm -r = recursively removes a directory and contents
    rm -rf = forcefully removes a directory and contents
13. 
