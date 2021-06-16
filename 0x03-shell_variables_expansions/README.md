Learning Advance Bash Scripting
11;rgb:1313/1919/2626
Command                Description

alias ls="rm *"  : script to create alias named ls with rm * as values stored in ls

echo Hello $USER  : Print Hello current user to the screen

export PATH=$PATH:/action  : To add path action to PATH as the last path

ls -l | wc -l  : To counts the number of directories in the PATH

printenv command : to list all environmental variable in linux

set command : To list all local and environmental variable in linux

export VARIABLENAME="variableValue" : To create local variable in linux

echo $((expression)) : To carryout Arithmetics operation in linux

echo $(( 2#$BINARY )) : To covert form base 2 to base 10

echo {a..z}{a..z} | tr ' ' '\n' | grep "oo"  : To create combination of two possible letter except oo. tr remove whitespace. \n move to next line. grep remove oo

printf "%0.2f\n" $NUM  	 : To print NUM variable value in two decimal places

