# .Dotfiles - Backend Week 1

## Welcome message
First I added a welcome message for the weather in Haarlem in the .bashrc with this code
> curl wttr.in/Haarlem
You can change "Haarlem with any place you want. 

## Aliases
After the welcome message I added some aliases to make work easy also in the .bashrc file
> alias subl='"/mnt/c/Program Files/Sublime Text 3/subl.exe"'
Open sublime text editor

> alias cdbackend='cd /mnt/d/school/jaar2/blok3/backend'
Go to backend folder in the D drive.
> alias cddownloads='cd /mnt/d/Downloads'
Go to download folder in the D drive.

## Git alias
I added some git aliases as well in the .bashrc file 
> alias gs='git status '
> alias ga='git add '
> alias gb='git branch '
> alias gc='git commit'
> alias gd='git diff'
> alias go='git checkout '
> alias gk='gitk --all&'
> alias gx='gitx --all'

### .GITCONFIG
Added aliases in the .gitconfig file
	co = checkout
        ci = commit
        st = status
        br = branch
*For Windows users*
> git config --global alias.co checkout
> git config --global alias.ci commit
> git config --global alias.st status
> git config --global alias.br branch

#### Prompt
After I did al the fancy stuf I changed my prompt in the .bashrc
> PS1='\[\e[37m\][\[\e[m\]\u\[\e[31m\]@\[\e[m\]\h \W \d\[\e[37;40m\]]\[\e[m\] '
The prompt will be [User@Hostname current directory current date]


