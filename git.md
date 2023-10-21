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

## create repo in github