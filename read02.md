# Seeing Your Remotes

By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

By using git remote -v, you can view all the remote URLs next to their corresponding short names.

##To create a new remote use following format:

** git remote add shortname url**
##Fetching
Fetching entails pulling data that you don’t have from a remote project.

**format:git fetch [remote-name]**

##To push
 your changes “upstream” for sharing, you would use the following git push command format:

** git push [remote-name][branch-name]**
## To rename a remote’s
 short name, use the git remote rename command.

## To remove 
a remote for whatever reason (e.g., a contributor has left the team, the server has moved), simply use the git remote rm command