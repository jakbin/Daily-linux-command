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
```bash
rm sample.txt
rm: remove regular file 'sample.txt' ? 
```