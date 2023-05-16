0. <o> => Create a script that creates an alias. Name ls, Value: rm *
==> alias ls="rm *"

1. Hello you. => Create a script that prints hello user, where user is the current Linux user.
==> echo "hello $USER"

2. The path to success is to take massive, determined action. => Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
==> export PATH=$PATH:/action

3. If the path be beautiful, let us not ask where it leads => Create a script that counts the number of directories in the PATH.
==> echo $PATH | tr ':' '\n' | wc -l
4. Global variables => Create a script that lists environment variables.
==> printenv

5. Local variables => Create a script that lists all local variables and environment variables, and functions.
==> set

6. Local variable => Create a script that creates a new local variable. Name: BEST, Value: School
==> BEST="School"

7. Global variable => Create a script that creates a new local variable. Name: BEST, Value: School
=> export BEST="School"

8. Every addition to true knowledge is an addition to human power => Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
==> echo $((128 + $TRUEKNOWLEDGE))
