# git-commands
Scripts to extend git functionality an speed up the day

## How to install

- Copy the scrypts files to `usr/local/bin` or equivalent
- Set up environment variables

On `~/.zshrc` or equivalent add:

```sh
export GIT_COMMANDS_BRANCH_PREFIX="<PREFIX>"
# override the default remote (orign)
export GIT_COMMANDS_REMOTE="upstream"
```

then source it

```sh
source ~/.zshrc
```


## Tips

Configure the git aliases by executing the script `config/aliases.sh`.

List aliases:

```sh
git config --global --get-regexp alias
```
