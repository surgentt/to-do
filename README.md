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

### Don't try and avoid conflicts
* We break stuff then let it fix

###SSH
* This is the better way to work with github
* SSH is a protocal for one computer to create a terminal with another computer
  * SSH - Secure Shell
  * Need an IP address as well as a Fingerprint

#### How can you have two computers can know who each other is, without either one knowing the password?
*One-Way function, Easy one direction and hard on teh other.
*Easy One direction, hard the other way. 

*'ssh-keygen'
  *Get a public key and a private key from this. 
  *ssh keys get put in 'cd ~/.ssh/'
  *share two public keys and one private key
  *cat id_rsa.pib

### Forking
*Github added this term.
*Really a repository with multiple remotes
*Flatiron School Students
  *We don't have acess to both remotes
*Second a lab is forked we pay attention to.
*Once pull request is submitted, we know the code is ready to be done
*Cloning is done anaymously 

### Pull Requests
*Now there is a note in the incoming repository that a pull request
*Can't create a pull request from command line, b/c they are not part of git.