# MQST-QComputing

Project: design a Turing Machine to perform the factoring task.

The decision table of the different TM created are stored in .txt files and an environment to simulate the TM is taken from (https://sandipanweb.wordpress.com/2020/08/08/simulating-a-turing-machine-with-python-and-executing-programs/) and stored in TuringSimulator.ipynb

The complete TM (4.2prog_factoring.txt) has been built using intermediate TM to archieve smaller tasks, such as initialization (2.1prog_initialsettings.txt) or multiplying (1.1prog_multiply.txt). They can also be found in the project to help with a better understanding of the working method. Also a report with detailed information about the algorithm and the final decision tables is in QComputingAssignment1.pdf. 

4.2prog_factoring.txt - The final design for the TM. Input example: '10001101'

4.0prog_factoring.txt - First version of the TM, also works but with a less efficient algorithm (an order of magnitude slower at least). Input example: '10001101'

2.1prog_initialsettings.txt - From the input creates two strings to use them as test to find the factors by multiplying. Input example: '10001101'

1.1prog_multiply.txt - From two strings separated by 2 blanks, gives the multiplication of those strings without erasing the factors. Input example: '1011__100111'

3.0prog_compare.txt - Comparison of the input and the result of the multiplication. Input example: '110111___11101__01001___100000101'
