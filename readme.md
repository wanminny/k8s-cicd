## gitops demo

> 1.  ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

       添加id_rsa.pub到私有仓库
       ssh -T git@github.com

> 2.  ssh-keyscan github.com >> ~/.ssh/known_hosts
> 3.  root@flexusx-412037:~/work/kind# more ~/.ssh/config
>     Host github.com
>     HostName github.com
>     User wanminny
>     IdentityFile ~/.ssh/id_rsa
