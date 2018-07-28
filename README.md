# VNC Viewer thru SSH tunnel

VNC Viewer is one of the most popular tool used to remotely connect to Linux server though is not slow and not secured. One of the way to make the secured connection is to use SSH tunnel. Instead of directly connect to the port 5901 of the remote server, we connect to the port 5901 on the local machine, SSH then forward to the data to the remote server thru the SSH port 22 which is secured


### Prerequesites

- Check the server

```
	systemctl get-default
```
<img src="docs/check-boot-level.png"/> 
