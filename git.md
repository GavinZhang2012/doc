## Github
* Create a github account: GavinZhang2012
* https://github.com/GavinZhang2012

### install git
* Download git in https://git-scm.com/download/win
* Install git
#### Create SSH key: 
* https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=windows
```
ssh-keygen -t ed25519 -C "gavin.zhangs2012@gmail.com"
```
* Copy SSH key to github
```
clip < ~/.ssh/id_ed25519.pub
```
* Show SSH key
```
cat ~/.ssh/id_ed25519.pub
```

## Config git
One time configuration
```
git config --global user.email "gavin.zhangs2012@gmail.com"
git config --global user.name "Gavin"
```

## create repo in github
### Follow below command when you first time to push code to this repo
1. Create repo in github
2. git init
3. git add .
4. git commit -m "learn how to use git"
5. git branch -M main
6. git push --set-upstream origin main
### Second time
1. git status
2. git add .
2.1 git diff
3. git commit -m "how to create repo"
4. git push

