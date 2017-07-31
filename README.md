# zshrc
Aliases and git setup 

- Install Homebrew
- Install npm
- Install IDE or text editor
- Install [theFuck](https://github.com/nvbn/thefuck)

Doublecheck : https://github.com/eklemen/ekDotfiles/blob/master/setup.sh

### Productivity

alias ll="ls -al"
alias storm="open -a PhpStorm ./"
eval "$(thefuck --alias merp)"

### npm stuffs

alias ni="npm install "
alias nig="npm install -g "
alias start="npm run start"
alias npupdate="npmu"
alias npmu="npm update"

### git stuffs
alias plod="pull origin Development"

### yarn stuffs

alias savedev="yarn add -D"
alias peer="yarn add -P"
alias test="yarn run test"
alias cov="yarn run test -- --coverage"
alias nocache="yarn run test -- --coverage --no-cache"

export PATH="/usr/local/sbin:$PATH"
export PATH="/usr/local/sbin:$PATH"
export PATH="$PATH:`yarn global bin`"

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm


