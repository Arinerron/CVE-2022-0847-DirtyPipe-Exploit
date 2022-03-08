# What is this

This is Max Kellermann's proof of concept for Dirty Pipe, but modified to overwrite root's password field in /etc/passwd and restore after popping a root shell.

**Side Note:** I do not claim any credit for finding this vulnerability or writing the proof of concept. This exploit is merely a small modification of Kellermann's proof of concept to enable quick/easy exploitation. Please read the original article on this extremely interesting vulnerability @ https://dirtypipe.cm4all.com/ when you get the opportunity. It really does deserve your time to understand it.

# How to use this

1. Compile with `./compile.sh` (assumes `gcc` is installed)
2. Run `./exploit` and it'll pop a root shell

# su: must be run from a terminal

If you get this error message:
1. Login as `root` with the password `aaron`.
2. Then, restore `/etc/passwd` by running `mv /tmp/passwd.bak /etc/passwd`

(oops sorry my laptop battery is dying and my charger broke so I don't have time to fix this the right now, sorry)

