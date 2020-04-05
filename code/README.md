# milestones-team19-crehling16-jjrice
milestones-team19-crehling16-jjrice created by GitHub Classroom


# MILESTONE 1 #

### helloworld.txt ###
Prints "hello world".

### octagon.txt ###
Draws a series of nested octagons. Demonstrates drawing, functions, 'while' loops and variables in Logo.
  
# MILESTONE 2 #
  
## Control Flow Code Snippets ##
The file listed below cover all control flow commands in LOGO. Each file contains a code snippet demonstrating the command. 
Below each listed file is a description of what command is being used and how the command works.
  
### p2_run.lg ###
Uses the RUN command which runs the logo instructions in the input list. In the file p2_run.lg, the file holds the procedure PrintWorld that will print the string "HelloWorld!" when the file is loaded and the procedure PrintWorld is entered.

### p2_runresult.lg ###
The file p2_runresult.lg uses the RUNRESULT command which runs the instructions in the input, the input is an instruction list. The file holds the procedure RESULT that will print the strings "First", "Second", and "Third" when the file is loaded and the procedure RESULT is entered.

### p2_repeat.lg ###
The file p2_repeat.lg uses the REPEAT command which takes an integer n and a instruction list and runs the instruction list n times. The file holds the procedure REPEATCHEER that prints out the strings "Hip", "Hip", "Horray", and "" three times when the file is loaded and procdure REPEATCHEER is entered.

### p2_forever.lg ###
The file p2_forever.lg uses the FOREVER command which runs the instructional list repeatdly until something inside the instructional list make the command stop, such as a STOP or THROW. The file holds the procedure 4FOREVER that prints the string "hi" until the command is killed or the logo console is closed.

### p2_repcount.lg ###
The file p2_repcount.lg uses the REPCOUNT command which outputs the repetition count of the innermost current REPEAT or FOREVER starting from 1. The repcount must be placed inside the loop to be used, for example, to print the current iteration of a loop. The file holds the procedure REPCOUNTLOOP that prints the value of the each iteration inside of a REPEAT command that loops 4 times.

### p2_if.lg ###
The file p2_if.lg uses the IF command which takes two parameters, the first being a boolean statement, and the second an instruction list that is run if the boolean expression returns TRUE.
The file holds the procedure PRINTTURE that contains an if statement that will evalutes to true and prints the string "TRUE". 

### p2_ifelse.lg ###
The file p2_ifelse.lg uses the IFELSE command that three parameters, the first being a boolean statement, the second and third are intruction lists that will run depending boolean expression returns true or false. If the boolean expression is true the first instruction list is run, else if the expression is false the second instruction list is run. The file holds the procedure PRINTFALSE that contains the ifelse command and outputs the string "x>0".

### p2_test_iftrue.lg ###
The file p2_test_iftrue.lg uses the command TEST, whcih remembers if an input was true or false to be used later in an iftrue or iffalse instructions, and the IFTRUE command, which runs the input if the most recent TEST command had a TRUE input. The file holds a local value x set to 7 and uses the TEST command to check if x<8. The IFTRUE command uses the result from the TEST command and prints the string "Test_Returned_True".

### p2_test_iffalse.lg ###
The file p2_test_iffalse.lg uses the commands TEST and IFFALSE, which runs the input if the most recent test had a FALSE input. The file conatins the same code as the file p2_test_iftrue.lg expect the TEST command tests if x>8 and the IFTRUE command is a IFFALSE command, which  outputs the string "Test_Returned_False".

### p2_stop.lg ###
The file p2_stop.lg displays the command STOP which ends the running of a procedure in which it appears. The file contains the procedure STOPFOREVER which runs the command FOREVER and stops when the command has iterated 10 times. The REPCOUNT is printed in each iteration to show that the FOREVER command stops after 10 iterations.

### p2_output.lg ###
The file p2_output.lg displays the command OUTPUT which outputs the value to the context in which it was invoked. The file holds the procedure OUTPUTX which uses the same code as p2_stop.lg except it replaces the command STOP with the command OUTPUT x, which returns the value in x. To view the output from the procedure run the command PRINT OUTPUTX, which will print the value of x that was returned by the procedure OUTPUTX.

### p2_catch.lg ###
The file p2_catch.lg displays the command CATCH which takes two parameters as input. The first parameter is the condition to be caught, in LOGO this is either a word, a boolean expression that returns true, or an error condition. The second parameter is an instruction that runs and if the output matches the first parameter, then CATCH command returns contorl to the command following the CATCH command, if it doesn't catch, then LOGO searches for another CATCH to be caught. The file holds the procedure CATCHWORD that contains one CATCH command that checks if the instruction, a print statement that prints the string "caught", given to the command prints the string "caught" and exits.

### p2_throw.lg ###
The file p2_throw.lg displays the command THROW which...

### p2_error.lg ###

### p2_pause.lg ###

### p2_countine.lg ###

### p2_wait.lg ###

### p2_bye.lg ###

### p2_maybeoutput.lg ###

### p2_goto.lg ###

### p2_tag.lg ###

### p2_ignore.lg ###

### p2_'.lg ###

### p2_for.lg ###

### p2_dowhile.lg ###

### p2_while.lg ###

### p2_dountil.lg ###

### p2_until.lg ###

### p2_case.lg ###

### p2_cond.lg ###
