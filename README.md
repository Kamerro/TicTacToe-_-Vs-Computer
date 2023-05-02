# TicTacToe-_-Vs-Computer
TicTacToe created with WFA with all controls generated in code, - Code in PL language ;)

## Table of contents
* [Code]
* [Pictures](#Pictures)
* [Technologies](#Technologies)



# Code code code code! 

How it works?
All controls are generated in code. The main window contains Panel control, and Panel control contain 9 Cells.
1 Cell is one object of class that inherits from "Label" Control. Why? How? Read for further info!

Enums!
In code I use Enums to mark if the player is the Cross or Circle. Same to the computer.
Of course we could use strings to mark sites, but the Enums are much more elegant :)

 Inheritance and why we use it? 
In code I create new control that inherit from Label. Label contain events and possibility for putting image into, so this is perfect choice for us!
Below in "Picture" section I put some screenshots of code, where the function is added to event "On Click" of created control.

How to generate controls in code 😲? 
Simply, we need to declare the control, set the size, location and add the control into our Form. More in "Picture" section.

Computer behavior. How to check the cells?
We only need to check if the selected cell is empty or not. We can use 2D array of int/bool as grid. If we put something into cell, change the value in that place.
In code I use format [0] -> empty cell, [1] -> player cell, [-1] -> computer cell. If the cell is !=0 then we can put there something!

# Pictures:
![Inheritance](https://user-images.githubusercontent.com/98419600/235795924-b8eed1a8-f91b-483b-9d6a-bcc82ec67f08.jpg)

Above is class that inherits from "Label". All we need to do is add some methods, that will change image of the control.


