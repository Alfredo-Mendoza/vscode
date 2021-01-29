as = !git add . && git status
e = config --global -e
lg = log --oneline --decorate --all --graph
rv = remote -v
s = status -s -b
slg = log --graph --abbrev-commit --decorate --date=relative --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all
