# shpass
A light shell-script password manager.

## usage
`shpass gen 18` - generate password with 18 characters  
`shpass add mail` - add account *mail* (will ask for account password, and gpg encryption pass)  
`shpass read mail` - read passowrd for account *mail* (will ask for gpg encryption pass)

## installation
**REQUIRES GPG TO BE INSTALLED**
1. clone repo
2. `chmod +x shpass`
3. copy to `/usr/local/bin`
  
**New install script**  
`bash -c "$(curl -fsSL https://raw.githubusercontent.com/i386sh/shpass/master/quick_install)`
