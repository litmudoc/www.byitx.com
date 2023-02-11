# www.byitx.com

:fire: :fire:

```shell
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```

```shell
git config --global user.name "Your Name"
git config --global user.email you@example.com
```

```shell
git config user.name "Your Name"
git config user.email you@example.com
```

## Github Multi Profile config
```shell
# gh alias set --shell {identifier} 'cp ~/.config/gh/hosts.yml.{identifier} ~/.config/gh/hosts.yml && gh auth status && git config --global user.name {username} && git config --global user.email {username@email.com}'
gh alias set --shell company 'cp ~/.config/gh/hosts.yml.company ~/.config/gh/hosts.yml && gh auth setup-git && gh auth status && git config --global user.name {username} && git config --global user.email {username@email.com}'
gh alias set --shell personal 'cp ~/.config/gh/hosts.yml.personal ~/.config/gh/hosts.yml && gh auth setup-git && gh auth status && git config --global user.name {username} && git config --global user.email {username@email.com}'
cat ~/.config/gh/config.yml
```

## Select Github Profile
```shell
gh company #or personal
gh auth status
```
