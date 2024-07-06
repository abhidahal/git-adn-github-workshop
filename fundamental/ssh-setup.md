# SSH Setup

## **git**

```
ssh-keygen -t rsa -b 4096 -C "<email>"
```

> run `sudo apt install openssh-client` if not working

```
eval "$(ssh-agent -s)"
```

```
ssh-add <private_key>
```

```
cat ~/.ssh/id_rsa.pub
```

```
git config --global user.name "Your Name"
git config --global user.email "youremail@yourdomain.com"
```
