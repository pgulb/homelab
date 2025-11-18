## set alias for downloaded kubeconfig

alias h='KUBECONFIG=~/.kube/homelab kubectl'
complete -o default -F __start_kubectl h

## set alias for helm
alias hh='KUBECONFIG=/home/pgulbinowicz/.kube/homelab helm'
complete -o default -F __start_helm hh
