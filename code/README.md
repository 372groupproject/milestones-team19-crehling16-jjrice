# milestones-team19-crehling16-jjrice
milestones-team19-crehling16-jjrice created by GitHub Classroom


# MILESTONE 1 #

### helloworld.txt ###
Prints "hello world".

### octagon.txt ###
Draws a series of nested octagons. Demonstrates drawing, functions, 'while' loops and variables in Logo.
  
# MILESTONE 2 #
  
## Control Flow Code Snippets ##
The files listed below cover all control flow commands in LOGO. Each file contains a code snippet demonstrating the command. 
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
The file p2_throw.lg holds the procedure THROWERROR which display the THROW command/ The procedure holds one line, the THROW command. When the file is loaded and the procedure is called, the THROW command is called and display what would happen if thrown.

### p2_error.lg ###
The file p2_error.lg displays the command ERROR which outs a list describing the error that was caught, if no error is caught, the ERROR command will output an empty list. The file holds the procedure 2ERROR that contains a SUM command that does not do anything after the command is run. After the SUM command, the ERROR command is run and outputs a list of the command that just casued the error, in this case the SUM command. 

### p2_pause.lg ###
The file p2_pause displays the command PAUSE which pauses what is currently running and enters an interactive pause. The user is prompter for instructions, as a toplevel, but with a prompt that inclides the name of the procedure in which PAUSE was invoked. Local variables of that procedure are avaliable during the pause. The file contains the procedure PAUSEPRINTX that holds a local variable x that is set to the value 5. The procedure pauses after declaring the local variable, prompting for user interaction. Try typing print :x which will output the value of x. To end the pause type continue. The command CONTINUE is also a control flow command. CONTINUE ends the current interactive pause.

### p2_wait.lg ###
The file p2_wait.lg displays the command WAIT which takes an integer variable time and delays further execution for a 60th of a second of the variable time. The file holds the procedure PRINTWAIT that prints the strings "Hip", "Hip", and "Horray" with a ten second pause in between each print.

### p2_bye.lg ###
The file p2_bye.lg displays the command BYE whcih exits from the LOGO console and returns to the operating system. The file holds the procedure ENDCONSOLE that when run closes the console in which the procedure was run.

### p2_maybeoutput.lg ###
The file p2_maybeoutput.lg displays the command .MAYBEOUTPUT which works like OUTPUT except that the expression that provides the input value might not, output a value in which case the effect is like STOP (This is an alternative to RUNRESULT). The file holds the procedure RESULTMBO which uses the command .MAYBEOUTPUT to output the string "Hi_from_MAYBEOUTPUT" from a print command.

### p2_goto_tag.lg ###
The file p2_goto_tag.lg displays the commands GOTO and TAG. The TAG command does nothing, the tags are used by the GOTO command. The GOTO command takes a word as a parameter and looks for a TAG command with the same input and continues running the procedure from the location of the TAG. The file holds the procedure GOTOTAG which conatins a GOTO and then two print statments with a TAG in between them. When run the procedure GOTO jumps over the first print and continues running after the TAG printing the string "Do_print_this".

### p2_ignore.lg ###
The file p2_ignore.lg displays the command IGNORE which does nothing, it is used when an expression evaluted a side effect and its actual value is unimportant, for example, the output from a SUM command. The file contains the procedure IGNORE2 which conatins an IGNORE surrounded by print statements. The first print statment prints "Ignoring_Sum" and the second prints "After_Sum" and the ignore function calculates the SUM of 2 and 3 but does nothing with summed value.

### p2_'.lg ###
The file p2_\`.lg displays the command \` which outputs a list equal to its input but with certain substitutions. The file p2_\`.lg contains the procedure SHOWLIST which uses the command SHOW to display what the command \` outputs. The commadn \` is given the list [print "foo] and outputs that list.

### p2_for.lg ###
The file p2_for.lg displays the command FOR which takes two parameters as input. The first parameter is a forontrol and the second is an instruction list. To read more about how LOGO for works visit https://people.eecs.berkeley.edu/~bh/v2ch14/manual.html. The file contains the procedure FORLIST that outputs the values 2, 3.5, and 5 when run.

### p2_dowhile.lg ###
The file p2_dowhile.lg displays the command DO.WHILE which takes an instruction list and true/false expression as inputs. The command DO.WHILE repeatedly evalutes the inputs in the instruction list until the true/false expression evaluates to false. The file contains the procedure DOWHILE which increments a variable summed by 1 each time until the variable is a value greater than 10. The variables value is printed out to display that the DO.WHILE command ran and then stop after meeting its end condtion. The contorl flow command WHILE does the same thing except the first input into command WHILE is the true/false expression and then the instruction list.

### p2_dountil.lg ###
The file p2_dountil displays the command DO.UNTIL which takes an instruction list and true/false expression as inputs. The command DO.UNTIl repeatedly evalutes the inputs in the instruction list until the true/false expression evaluates to True. The file contains the procedure DOUNTIL which increments a variable summed by 1 each time while the variable is a value less than 10. The variables value is printed out to display that the DO.UNTIL command ran and then stop after meeting its end condtion. The contorl flow command UNTIL does the same thing except the first input into command UNTIL is the true/false expression and then the instruction list.

### p2_case.lg ###
The file p2_case.lg displays the command CASE which takes two parameters as input. The first parameter is a value and the second is a list of lists (clauses). To read more about how CASE works visit https://people.eecs.berkeley.edu/~bh/v2ch14/manual.html which is a link to a user's manual explain the introcacies of CASE. The file contains the procedure CASETEST that searches for the string "w" in a list of stirngs, if the string is found within the list of strings, then "true" is printed, if it cannot, then "false" is printed.

### p2_cond.lg ###
The file p2_cond.lg displays the command COND which takes a list of lists (clauses) as input. To read more about how clauses work vist https://people.eecs.berkeley.edu/~bh/v2ch14/manual.html. The file contains the procedure CONDTEST which runs the COND command on a list of lists and outputs the string "Condition's_Output".

## p2_feature ##
The program uses commands from the control flow snippets to out a fibnacci sequence from 0 to 511229.

# MILESTONE 3 #

### p3_word.txt ###

This file demonstrates declaring words with MAKE, and merging them with WORD.

### p3_list.txt ###

Demonstrates creating a list from hard-coded input, accessing the first/last indices of that list, accessing the tail of the list (for list processing purposes!), and converting lists to arrays.

### p3_array.txt ###

Demonstrates the features of arrays such as ARRAY, ITEM and SETITEM.

### p3_fail.txt ###

Demonstrates a type error generated by the Logo interpreter by attemping to create a new word from a word and a list.

# MILESTONE 4 #

### p4_pprocedure.lg ###
The file p4_procedure.lg demonstrates Logo procedures. The file contains the procedure EXAMPLE1, rhat when run, prints a string with an explaination about the procedure and what is does. The procedure then uses the REPEAT command to prin teh string "This is example 1" four times.

### p4_parametes.lg ###
The file p4_parameters.lg demonstrates Logo's procedure parameter passing. The file contains the procedure EXAMPLE2 takes two integers as input. The procedure prints the value of the passed parameters and prints the product of the two integers. This shows that the procedure can both accept and use passed in values. 

### p4_load.lg ###
The file p4_load.lg demonstrates Logo's ability to import files containing procedures that can be use in the file that it was loaded. The file imports the two file mentioned above and calls the procedure within each file. 
