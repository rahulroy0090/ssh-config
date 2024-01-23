
How to configure and use SSH with GitHub on Ubuntu?

## Genteated the ssh key.
ssh-keygen

## open the ssh public key.
cat /home/user/.ssh/id_rsa.pub

### Now, Add the ssh key in the github accounts.

1). Go to setting.
2). Add ssh key.
3). Save


### Now, Create a new ssh-config repository in github accounts.
I have created ssh-config repository in github.

### Now, clone the github using ssh of github.
git clone git@github.com:rahulroy0090/ssh-config.git

### Now, Create the file for insert into the ssh-config repository of github.
touch rahul.txt
touch thor.txt

### Now, Check the status of gitHub.

git status


### Now add 
git add .

git commit -m "ssh-config"


### Now, add the email id and your gitHub username.

git config user.email "abouthack4998gmail.com"

git config user.name "Rahul Kumar"

git commit -m "ssh-config"

### Now, push the file into the gitHub.

git push -u origin main

### Check the branch name.
git branch










