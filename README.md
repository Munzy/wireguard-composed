# wireguard-composed
A wireguard server docker-composed with Unbound DNS.


## cmulk/wireguard-docker


https://github.com/cmulk/wireguard-docker/tree/buster

### First Run
If the wireguard kernel module is not already installed on the __host__ system, use this first run command to install it:
```
docker run -it --rm --cap-add sys_module -v /lib/modules:/lib/modules cmulk/wireguard-docker:buster install-module
```
