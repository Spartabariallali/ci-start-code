# Why should we use SSH?

### The two methods to clone repos: 
` SSH and HTTPS `
### There are two types of repos:
 `public repos` and `private repos`

### creating a ssh key for an individual repo
- generate the key on local system 
- copy and paste the key from the local system to the specific repo om github (ci-start-code)
- .ssh folder where we have ssh keys available 
- name the new key as 'my name' for example Bari
- `cd` home directory
- find `.ssh`
- run the command `ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`
- name the new key as your name 
- go to your github to the specific repo
- click on setting
- click on deply keys
- add deploy 

### It is essential to give descriptive/informative names 


