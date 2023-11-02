# .bashrc

```bash
source <(kubectl completion bash)
echo "source <(kubectl completion bash)" >> ~/.bashrc
alias k=kubectl
complete -F __start_kubectl k

alias kd="k describe"
alias grep="grep -i"
export do="--dry-run=client -o yaml"
alias kn='kubectl config set-context --current --namespace'
```

# .vimrc

```vim
set tabstop=2
set expandtab
set shiftwidth=2
set autoindent

set nu
set ignorecase
syntax on
```
