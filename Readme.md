# Shell Commands!
## Alias
1. Create alias: `alias la='ls -l -a --color=auto'`

## File Commands
1. More info: `ls -F`
1. Show hidden: `ls -a`
1. Long Listing auto color: `ls -l -a --color=auto`

## Dir Commands
1. List contents of dir: `ls`
1. Create Dir: `mkdir mydir`

## SSH
### Add New Key
1. Generate key: `ssh-keygen -t rsa -b 4096` 
1. Copy to .ssh: `mv <filename> /home/ubuntu/.ssh`
1. Start ssh agent: `eval $(ssh-agent -s)`
1. Add key: `ssh-add <youkeyfile>`

## Misc
1. Last Arg: `!$`
1. Read Env or shell var: `echo $PATH` wherer PATH is the var name.

## Functions
1. Set Function: `function set {}`

## Bash
1. Clear screen: `clear`
1. Read input: `read VAR_NAME` then use the variable
