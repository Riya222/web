#creating account 
##Then created an empty repository
# Cloning a repository and branching
## Cloning that repository into our local system
```git clone repository url```
A folder named "SD" is created
## Adding a file into the created folder
The file is added to the  local repository using the command ```git add FILE NAME``` and commit it with a commit message using the command ```git commit -m "MESSAGE"``` 
###pull the changes before pushing
### Push the created file to the master node 
Pushing the changes into master using ```git push origin master```
## Branch
### Created a new branch 
 Using the command ```git branch BRANCH NAME``` a branch is created or to directly get into the branch we use the command a

Checkout the branch using ```git checkout -b BRANCH NAME```

##Merging 

Merge the branch using ```git merge BRANCH NAME```. Now the created branch is merged with the master node.
Now the changes can be viewed using a graph with the command ``` git log --graph```.

