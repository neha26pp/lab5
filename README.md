# SWENG 421- LAB 5
There is a computational system COMP. The names of its computational modules are stored in file 
“modules.txt”. New ones can be appended to the end of the file. The system displays the module names 
on GUI in an ascending order. Some modules may require the user input, and a dialog will pop up. The 
user can randomly pick a module to perform computation. In the beginning, the default value is 0 and the 
value is updated based on the later computations of the chosen modules. 
Five modules can accept an input, and they are Initialize, Sum, Subtract, Product and Power. The 
Initialize sets the value to the input value, the Sum adds the input value to the current value, the Subtract 
deducts the input value from the current value, the Product multiplies the input value to the current value, 
and the Power treats the input as an exponent to the current value. There is one other math module Log 
that does not need an input. This module simply calculates the logarithm to the current value. Note that 
new modules are developed incrementally, and the goal is to achieve no code change to the existing 
system. Make sure the inheritance relationship of the design is correctly modeled, because not all 
modules accept an input argument. In other words, a class should only own methods that it can call.  
(4 pts) Submit the UML class diagram design and circle the applied design patterns in the diagram. 
Provide all required attributes, methods, classes, and relationships. (4 pts)
(6 pts) Implement the system in C#. Make sure that the GUI can easily accommodate the addition or 
removal of modules in the modules.txt file. Hint: ListBox and ComboBox are easier to display multiple 
items. (6 pts)
