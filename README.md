# Description
Who has never wished to have autocompletion on the cli of Zimbra ?  
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

    git clone https://github.com/wolfyzvf/Zimbra-Collaboration-Bash-Completion  

2. move the zmprov file to /etc/bash_completion.d folder  

    mv Zimbra-Collaboration-Bash-Completion/bash_completion.d/zmprov /etc/bash_completion.d/  

3. make it executable  

    chmod +x /etc/bash_completion.d/zmprov

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

# License
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
