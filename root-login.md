# Enable/Disable passworth Authentication via SSH

* login as root, or account that has read access to /etc/ssh/sshd_config file
* edit config file

`vi /etc/ssh/sshd_config`

* Ensure password authentication is turned off

`PasswordAuthentication no`

* Save file by hitting escape key and typing in shorthand for 'write, quit, save':

`:wq!`

# Disable Root login

* Follow the same steps as above but also ensure PermitLogin is set to no

`PermitRootLogin no`
