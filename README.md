# shpass
A light shell-script password manager.

## usage
`shpass gen 18` - generate password with 18 characters
`shpass add mail` - add account *mail* (will ask for account password, and gpg encryption pass)
`shpass read mail` - ask for encryption pass, and decrypt.

## installation
1. clone repo
2. `chmod +x shpass`
3. copy to `/usr/local/bin`

