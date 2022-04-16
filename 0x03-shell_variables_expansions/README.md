# shell, variables expansions
alias ls="rm *" : creates script named alias rm *
echo "hello $USER" : prints the name of the current user 
PATH=$PATH:/action : add action to the path action must be the last directory
echo $PATH | tr ":" "\n" | wc -l: a script that count the number directories in the path
printenv : list environnement variables 
