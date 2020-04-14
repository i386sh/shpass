# shpass
A light shell-script password manager.

## usage
`shpass gen 18` - generate password with 18 characters  
`shpass add mail` - add account *mail* (will ask for account password, and gpg encryption pass)  
`shpass read mail` - ask for encryption pass, and decrypt.  
`shpass pull` - pull passwords from server (requires auth from server)
`shpass push` - push passwords to server (requires auth from server)

## installation
**REQUIRES GPG TO BE INSTALLED**
1. clone repo
2. `chmod +x shpass`
3. copy to `/usr/local/bin`

