# my-aliases

source <(kubectl completion bash)
complete -F __start_kubectl k
alias k=kubectl
alias g=git
alias gs='g status'
alias ga='g add'
alias gcm='g commit -m'
alias gpuo='g push -u origin'
alias gp='g push'
alias gcb='git checkout -b'
alias kg='k get'
alias kgp='k get po'
alias kgns='k get ns'
alias kdel='k delete'
alias kdes='k describe'
alias kgpn='k get po -n'
alias gr='grep'
alias kdesp='k describe po'
alias klogs='k logs'
alias c=clear
