# zshrc
Aliases and git setup 

- Install Homebrew
- Install npm
- Install IDE or text editor
- Install [theFuck](https://github.com/nvbn/thefuck)

Doublecheck : https://github.com/eklemen/ekDotfiles/blob/master/setup.sh

## Aliases:

### Productivity

- alias ll="ls -al"
- alias storm="open -a PhpStorm ./"
- eval "$(thefuck --alias merp)"

### npm stuffs

- alias ni="npm install "
- alias nig="npm install -g "
- alias start="npm run start"
- alias npupdate="npmu"
- alias npmu="npm update"

### git stuffs
- alias plod="pull origin Development"

### yarn stuffs

- alias savedev="yarn add -D"
- alias peer="yarn add -P"
- alias test="yarn run test"
- alias cov="yarn run test -- --coverage"
- alias nocache="yarn run test -- --coverage --no-cache"

- export PATH="/usr/local/sbin:$PATH"
- export PATH="/usr/local/sbin:$PATH"
- xport PATH="$PATH:`yarn global bin`"

- export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm


# Git Config

Type this in letter for letter. 

[alias]
- cam = !git add -A && git commit -m
- cob = checkout -b
- com = checkout master
- cod = checkout development
- co = checkout
- la = "!git config -l | grep alias | cut -c 7-" 
- last = checkout @{-1}
- pretty = log --pretty=format:"%C(yellow)%h\\ %ad%Cred%d\\ %Creset%s%Cblue\\ [%cn]" --decorate --date=short
- s = status
- save = !git add -A && git commit -m 'work in progress...savepoint'
- undo-commit = reset HEAD~1 --mixed

