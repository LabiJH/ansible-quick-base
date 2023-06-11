# ansible-quick-base
A quick base Setup for an Debian based Linux Server with the Docker Suite.

# What does it do?
- Updates & Upgrades all Packages:
-   vim
-   htop
-   neofetch
-   tmux
-   speedtest-cli
-   docker-ce
-   docker-ce-cli
-   containerd.io
-   docker-buildx-plugin
-   docker-compose-plugin

- Disables SSH Password Authentication
- Disables SSH Root Access
- restars the SSH Daemon on cfg change.

BE CAREFUL! 
If you dont know what you are doing, you can easily lock yourself out of your servers as you can not use root access or password based login via SSH.
