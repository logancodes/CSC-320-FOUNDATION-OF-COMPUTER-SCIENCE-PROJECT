CSC 320 PROJECT

Members: Ushanth Loganathan
	 Kushal Patel

You will have to install the Anaconda pyhton ppackage first.
It is available here : http://continuum.io/downloads

After installing the package, open the anaconda command prompt
and compile the program sat.py

The input that this program takes should be in a file called this.txt 
which should be in the same folder as sat.py and in a 9*9 format as:

1...4...7
...2...6.
...6..4.8
..2...7.5
.........
.........
.........
.........
2..3..8.9


This program will display the solved sudoku on the command prompt itself.
A file with the list of clauses will be generated and will be saved as 
'clauses for solver.txt' in the same folder as well.

This program makes heavy use of pycosat to solve the sudoku as it is an efficient 
solver. More on this is covered in the report.