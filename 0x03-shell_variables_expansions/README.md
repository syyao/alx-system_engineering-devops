# shell, variables expansions
alias ls="rm *" : creates script named alias rm *
echo "hello $USER" : prints the name of the current user 
PATH=$PATH:/action : add action to the path action must be the last directory
echo $PATH | tr ":" "\n" | wc -l: a script that count the number directories in the path
printenv : list environnement variables
set | less : list all local variables and environnment variables and functions 
BEST:School : creata a local variable environnment
export Best:School create a global variable 
echo ${(TRUEKNOWLEDGE+128)}: resultat of addition of 128 with a value stored
echo $(($POWER/$DIVIDE)) : resutat of POWER divide by DIVIDE 
echo $(($BREATH**LOVE)) : resultat of BREATH exponent LOVE 
echo  $((2#$BINARY)) : convert number from base 2 to 10
echo {a..z}{a..z} | tr ' ' '\n | grep -v oo : create a script that prints all possible combinations of the letters excepted oo 
echo (%0.2f\n) $NUM : prints num with wo decimal places followed by a line 
echo '%x/n' $DECIMAL : pritns every other line from the input starting with the first line

