# The Program #

# How to run the program #
Go to https://people.eecs.berkeley.edu/~bh/logo.html to download the UCBlogo command window. After downloading UCBLogo, a shortcut will be added to your desktop. Click on the shortcut and once the command window is open click on "File" -> "Load Logo Session", this will open your file explorer. Navigate to the folder that contains the file main.lg along with the other files listed below and double clidk on main.lg, this will load the contents of the file into the command window. Once loaded type MAIN into the window and the program will run.

# Predefined Procedures #
The files listed below will be imported and used in the main program file. Each file contains a procedure that contains a set of instructions that will produce a turtle graphic. "Tutrle graphics are vector graphics that are produced by using a cursor (the "turtle") on a Cartesian plain" (WIKI). The turtle is a little icon on the screen that moves as the user inputs commands. The main file will randomly call these imported procedures and produce a randomly drawn turtle graphic.

### triangle.lg ###
The file contains the procedure TRIANGLE :distance that when invoked creates a (45, 45, 90) triangle with sides of length :distance.

### square.lg ###
The file contains the procedure SQUARE :length that when invoked creataes a square with sides of length :length.

### rectangle.lg ###
The file contains the procedure RECTANGLE :width :height that when invoked creataes a rectangle with width :width and height :height.

### s.lg ###
The file contains the procedure S :size that when invoked creates an s with size :size.

### mirroredRhombus.lg ###
The file contains the procedure BACKWARDS :size that when invoked creates two rhombii with two sides the size of :size, drawn mirrored to each other.

### diamond.lg ###
The file contains the procedure DIAMOND :distance that when invoked creates a DIAMOND with sides of length :distance.

### lotus.lg ###
The file contains the procedure LOTUS :size that when invoked creates 8 diamonds with sides of length :size.

### main.lg ###
The file contains the procedure MAIN that when invoked randomly draws 1 to 1000 different shapes and uses the files listed above.
