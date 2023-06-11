# ansible-quick-base
A quick base Setup for an Debian based Linux Server with the Docker Suite.
This is mainly used in my homelab.

# What does it do?
- Updates & Upgrades all Packages
- Disables SSH Password Authentication
- Disables SSH Root Access
- Install the Docker Suite
- restarts the SSH Daemon on cfg change.

# BE CAREFUL! 
If you dont know what you are doing, you can easily lock yourself out of your servers as you can not use root access or password based login via SSH.
You should not use this in your private/production environment.
