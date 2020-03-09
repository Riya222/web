#Report on git operations</br>
###.Firstly, created a team consists of 4 members. 
###Creating repository
our team leader created an empty repository named "SDlab2" and invited as to collaborate into the repository.</br>
##Clone</br>
We the team members cloned the remote repository.</br>
First commit was created by the master and then we pull the master origin into our local repository as ```git pull origin```.</br>
##Add and commit
Then we add our files as ```git add.filename```and committed the file using a meaningful commit message as ```git commit -m "First commit```.
##Push
Finally pushed the file into the remote repository using ```git push origin```.</br>
##Fetch
Fetching the changes using ```git fetch origin```,and again commit the changes and push to origin.
##Branching
Each member created their respective branches as ```git branch name```and committed inside the branch then, push the branch to the master node and viewed the same ```git checkout master```.</br>
##Merge
After completing all the creations of branches we merged the branches to the master node as ```git merge nameof branch``` to make it available to other team members.</br>
##Graph
These branches are viewed as a graph using the command "git log --graph --oneline --all".
##Checkout and push the changes
```git push --set-upstream origin branchname``` push the current branch and keep the remote as upstream.

