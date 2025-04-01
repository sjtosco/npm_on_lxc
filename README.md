# npm_on_lxc
Nginx Proxy Manager manually installed on existing LXC on Proxmox

Based on [Proxmox Helper Scripts](https://community-scripts.github.io/ProxmoxVE/scripts?id=nginxproxymanager) but somethings updated. Moreover, you dont need run it on Proxmox.

## Steps:

1. Manually create LXC on Proxmox.
2. Install this utilities: `apt update; apt install vim htop git -y`.
3. Clone this repo and enter inside folder.
4. Give permissions to install script: `chmod +x install_npm.sh`.
5. Execute and wait...
6. Enjoy
