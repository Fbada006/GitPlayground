# GitPlayground
Nothing to see here. Just playing around with git

1. git log 
   - Get all the commit history 
   --oneline flag to get less scrolling
   -(-number) such as -2 to limit the git log to a specific number of commits
   --stat to get more details of files changed in each commit
   --patch for the full diff fo each file for each commit
   
2. git rm <a fully qualified filename>
    -Tell git to delete the file

3. git rm --cached <a fully qualified filename>
    -Tell git to stop tracking the file but not delete it

4. git mv oldName newName
    -Rename a file with git      
