# :fire: www.byitx.com :fire:

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
```
# gh alias set --shell {identifier} 'cp ~/.config/gh/hosts.yml.{identifier} ~/.config/gh/hosts.yml && gh auth status'
gh alias set --shell company 'cp ~/.config/gh/hosts.yml.company ~/.config/gh/hosts.yml && gh auth status'
gh alias set --shell personal 'cp ~/.config/gh/hosts.yml.personal ~/.config/gh/hosts.yml && gh auth status'
cat ~/.config/gh/config.yml
```

## Select Github Profile
```
gh company #or personal
gh auth status
```

