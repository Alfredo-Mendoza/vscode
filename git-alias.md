### Agregar todos los archivos al stage y ver estatus
as = !git add . && git status

### Ver confguración global
e = config --global -e

### Ver logs
lg = log --oneline --decorate --all --graph

### Remover archivo
rv = remote -v

### Ver estatus y rama
s = status -s -b

### Ver super log
slg = log --graph --abbrev-commit --decorate --date=relative --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all
