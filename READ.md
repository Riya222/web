# Cloning a repository and branching
## For team work including collabrators
### Cloning a repository into local system
```git clone repository url```
A folder named "SDLAB2"  created
### Adding our own file into folder
creating a file  and add it into git local repository using the command ```git add dayal.c``` and commitb it with a message
### Push the changes
Pushing the changes into master using ```git push origin master```
if push is rejected , pull it and push again

### Fetching
Fetching the changes using 
```git fetch origin master```


Commit the changes using ```git commit -m "commit dayal.c"``` and push back

## Branch
### Created a new branch for new work
Using the command ```git branch branch1```


Checkout the btranch using ```git checkout branch1```

Make any change in any file that cloned from remote repository. Here updation is done on add.c file. Then commit it using ```git commit -a -m "updated add.c"``` 

Merge the updation using ```git merge branch1```. Now the created branch is merged with parent.
After committing a change and attempting to push the changes,To push the current branch and set the remote as upstream, use

``` git push --set-upstream origin branch1 ```


Now the changes made with branch1 is reflected on master branch.
