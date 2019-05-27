# dockerc

```bash
wget https://github.com/alpinelinux/docker-alpine/raw/29db8d88a0387f56cc77b270f72d33b9d48fd021/x86_64/alpine-minirootfs-3.9.4-x86_64.tar.gz
tar xzf alpine-minirootfs-3.9.4-x86_64.tar.gz -C ro
otfs
sudo `which go` run dockerc/mainc.go
```

# references

- https://github.com/opencontainers/runc
- https://github.com/kubernetes-incubator/cri-tools
- https://github.com/opencontainers/runtime-tools
- https://github.com/genuinetools/riddler
- https://github.com/genuinetools/netns
- https://github.com/containernetworking/cni
- https://github.com/containernetworking/plugins
- ctr
- crictl
- boss
- stellar

- https://medium.com/@vikram.fugro/container-networking-interface-aka-cni-bdfe23f865cf
- https://www.jianshu.com/p/62e71584d1cb

# alpine rootfs

https://github.com/alpinelinux/docker-alpine/raw/29db8d88a0387f56cc77b270f72d33b9d48fd021/x86_64/alpine-minirootfs-3.9.4-x86_64.tar.gz

# work

- CNI Container Network Interface
- CRI Container Runtime Interface
- OCI Open Container Initiative

# CMD

- pstree
- dmesg
