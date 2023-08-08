1.	alias ls="rm *" : Creates an alias		
2.	echo "hello $USER" : Prints `hello user`, where user is the current user		
3.	export PATH=$PATH:/action :  Add `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program		
4.	echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) : Counts the number of the directories in the `PATH`		
5.	printenv : Lists environment variables	
6.	set : Lists all local variables and environment variables, and functions		
7.	BEST="School" : Creates a new local variable named BETTY		
8.	export BEST=School : Creates a new global variable named HOLBERTON	
9.	echo $(($TRUEKNOWLEDGE + 128)) : Prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line	
10.	echo $(($POWER / $DIVIDE)) : Prints the result of `POWER` divided by DIVIDE, followed by a new line	
11.	echo $((BREATH**$LOVE)) : Displays the result of `BREATH` to the power LOVE
12.	echo "$((2#$BINARY))" : Converts a number from base 2 to base 10
13.	echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" : Prints all possible combinations of two letters, except `oo`
14.	printf "%.2f" $NUM | sort : Prints a number with two decimal places. The number is stored in the environment variable NUM
15.	printf '%x\n' $DECIMAL : Converts a number from base 10 to base 16
16.	tr 'A-Za-z' 'N-ZA-Mn-za-m' : Encodes and decodes text using the rot13 encryption perl -lne 'print if $. % 2 ==1' : Prints every other line from the input, starting with the first line
17.	echo $(printf %o $(($((5#$(echo $WATER | tr 'water' '01234'))) + $((5#$(echo $STIR | tr 'stir.' '01234'))))) | tr '01234567' 'bestchol') : Adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result

