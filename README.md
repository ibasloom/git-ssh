# Git-ssh 
How to Set the SSH key for GitHub

#### Optional 

[Download Visual Studio Code](https://code.visualstudio.com/download)

#### To check if Git is installed on your system
```
git --version
```

```
git
```
[Download Git](https://git-scm.com/downloads)

[Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

```
git config --global user.name "John Doe"
```
```
git config --global user.email johndoe@example.com
```

####  is used to open the global Git configuration file in a text editor
```
git config --edit --global
```
#### Set Visual Studio Code as Default Editor
```
git config --global core.editor "code --wait --new-window " 
```
#### To check SSH Key is there or not
```
ls al ~/.ssh
```
[Reffrence link GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=mac)

```
ssh-keygen -t ed25519 -C "your_email@example.com"
```

```
eval $(ssh-agent -s)
```

```
ssh-add ~/.ssh/id_rsa
```
```
ssh -T git@github.com
```
