## Git alias
```
alias gc="git commit -m"
alias ga="git add"
alias gp="git push"
alias gpo="git pull origin"
alias gpl="git pull"
alias gcb="git checkout -b"
alias gco="git checkout"
alias gs="git status"
alias gbd="git branch -D"
alias gfo="git fetch origin"
function gbdfc(){
    git branch -D "$1" && git fetch origin "$1" && git checkout "$1"
}
```

## Bstack relevant alias
```
alias yrds="yarn run dev:sync"
alias yrdl="yarn run dev --product=live"
alias yrdal="yarn run dev --product=applive"
alias yrda="yarn run dev --product=automate"
alias yrdaa="yarn run dev --product=app_automate"
alias ngx="sudo nginx"
alias ngxr="sudo nginx -s reload"
alias bi="bundle install"
alias mig="rake db:migrate; rake db:seed"
alias bsfe="cd Coding/browserstack-fe && yrdl"
alias leg="cd Coding/browserstack-fe/legacy && yrds"
alias nu18="nvm use v18.10.0"
alias bifrost="turbo run storybook --filter bifrost"
alias webex="turbo run storybook --filter webex"
```

## maxfile increase
```
alias maxfile="sudo sysctl -w kern.maxfiles=20480 && sudo sysctl -w kern.maxfilesperproc=18000"
```