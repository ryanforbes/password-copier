# password-copier
A small script to find a password and put it in your clipboard. Works on OSX. Not sure about anything else.

Format a file `~/.creds` with a short key on one line and the corresponding password on the following line. `chmod 600 ~/.creds`. Run `p <somekey>`. If a password is found, you'll get a 👍 and that password will be in your clipboard. Otherwise, 👎.
