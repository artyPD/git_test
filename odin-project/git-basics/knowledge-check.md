## Git Basics

1. By clicking on the 'New' button on the website, entering a name and clicking 'Create' repsitory.
2. There are a few options namely via, HTTPS, SSH and directly from the github CLI.
3. The default name of the remote connection is "origin" with the defailt branch being "master" unless changed to something else like "main".
4. "origin" is the name given to the remote connection to the remote repository on Github.
5. "main" is the name of the default branch in the repository. The "root branch" if you will. This can be changed; in this case the default name for the default branch was changed from "master" to "main".
6. Git uses two stages to save files to repositories. The first stage is "modified" or "unstaged" which, as the name suggests, means changes were made to the files but have not been prepared to be commited. Which leads me to the next stage: "staged". Staged files are files ready to be commited into the repository.
7. Check the status by using `git status` in the terminal.
8. Add files to the staging area by using `git add [filename or "." to indicate all files in the current directory]`.
9. Commit files in the staging area with `git commit -m "Insert useful and non-hallucinogenic message here"`.
10. Push changes to the remote repository on Github with `git push`.
11. Look at the history of previous commits with `git log`.
