# Description
Who has never wished to have autocompletion on the cli in Zimbra ?
This project is here to solve this problem and help the sysadmin life.

# Requirements
The autocomplete file use the following packages :
- awk
- sed
- tr
- bash-completion for Ubuntu
- bash_completion for CentOS - RHEL

# Installation
1. first clone the project
    git clone
2. move the zmprov file to /etc/bash_completion.d folder
    mv
3. make it executable
    chmod +x zmprov

## Ubuntu
    apt-get install bash-completion

## CentOS
Turn on EPEL repositories and then :
    yum install bash-completion

# Provides
1. Autocompletion on accounts/server
2. Autocompletion on accounts/server attributes
3. Autocompletion on logging attributes

# Roadmap
1. Autocompletion on the domain
2. Add help when autocomplete a command
3. Add automcompletion for the zmmailbox command
