# Miscelaneous

## Git help

```
ssh-keygen -t ed25519 -C "shell5@gitlab"
```

```text
ssh -Tv git@gitlab.com
```

```bash
root@madrid:~# cat .ssh/config 
# GitLab.com
Host gitlab.com
  Preferredauthentications publickey
  IdentityFile ~/.ssh/gitlab_ed25519
```

```bash
git clone ssh://git@gitlab.com/shell5/hackthebox
cd hackthebox/

git add .
git push
git commit

git pull

```

