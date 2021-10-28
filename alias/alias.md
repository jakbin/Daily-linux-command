1. To create an alias to clear the screen.
```bash
alias cls='clear'
```

2. To create an alias 'ls' to change the default action of ls.
```bash
alias ls='ls --a'
```

3. To create various alias using cd command to go into to sub-sub directories.
```bash
alias ..='cd ..' 
alias ...='cd ../..'
alias ....='cd ../../..'
```

4. To create alias to display present working directory.
```bash
alias .='echo $PWD'
```

5. To create alias to prevent accidental deletion.
```bash
alias rm='rm -i'
```
How to use it.
```bash
rm sample.txt
rm: remove regular file 'sample.txt' ? 
```
6. Some ls alias
```bash
alias ls='ls --color=auto'
alias ll='ls -l'
alias lla='ls -la'
alias la='ls -A'
```
7. Some alias for making command output colorful
```bash
alias dir='dir --color=auto'
alias vdir='vdir --color=auto'
alias grep='grep --color=auto'
alias fgrep='fgrep --color=auto'
alias egrep='egrep --color=auto'
alias diff='diff --color=auto'
alias ip='ip --color=auto'
```