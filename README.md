### Remote 

* A remote is for collaboration. It points the information to another point in time. 

### Why use multiple remotes?

* Open source projects, you use a fork
* Origin is your personal fork
  * Basically a clone. 
* Eventually if you get access to main repo
  * You can get access to the main remote
* Rails is your personal repository tha tyou are pulling from. 

### Pushing to Branches

* It is important to specify which branch you are pushing two
  * If you 'git push' git will give you an error unless you specify which branch you are actually pushing too. 
  * ex. 'git push origin master'
    * origin is the remote name, master is the branch

### Branching

* 'git checkout -b'
  * Stage changes and uncommitments will follow you around to the new branch

### Delete a remote branch
* 'git push origin :please-work'
  * Prior to the : we are telling it nothing, after is the name of the remote