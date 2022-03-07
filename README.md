# What is this

This is Max Kellermann's exploit POC for DirtyPipe, but modified to overwrite root's password field in /etc/passwd and restore after popping a shell.

# How to use this

Run `./compile.sh` then `./exploit` and it'll pop a root shell.

# su: must be run from a terminal

1. If you get this error message, login as `root` with the password `aaron`.
2. Then, restore `/etc/passwd` by running `mv /tmp/passwd.bak /etc/passwd`

(oops sorry my laptop battery is dying and my charger broke so I don't have time to fix this the right now, sorry)
