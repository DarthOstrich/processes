# Enable/Disable passworth Authentication via SSH

* login as root, or account that has read access to /etc/ssh/sshd_config file
* edit config file

`vi /etc/ssh/sshd_config`

* Ensure password authentication is turned off

`PasswordAuthentication no`

* Save file by hitting escape key and typing in:

`:wq!`
