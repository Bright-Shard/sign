To use signing:

- `git config --global commit.gpgsign true`
- `gpg --list-keys` & find the key on the Yubikey
- `git config --global user.signingKey <key from gpg>`
