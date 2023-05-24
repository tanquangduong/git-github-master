# git-github-master
Master git and github cmd, ssh, etc


# Create SSH key for Github repo security
```
# create ssh key in your pc
ssh-keygen -t ecdsa -b 521 -C "your_email@gmail.com"

# list .ssh
ls -al ~/.ssh

# add it to the SSH agent
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ecdsa

# read ssh key with cmd 'cat'
cat ~/.ssh/id_ecdsa.pub

# then copy SSH key and paste it to new SSH key section in your github/settings
```