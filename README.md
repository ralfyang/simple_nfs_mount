# simple_nfs_mount
## How to use
  * Have to change the [IPADDRESS] to NFS server ip
```
curl -sL bit.ly/nfsmount | sed -e "s/\$1/[NFS SERVER IPADDRESS HERE]/g" | sudo bash 
```
