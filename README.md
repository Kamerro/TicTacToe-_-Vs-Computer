# TicTacToe-_-Vs-Computer
TicTacToe created with WFA with all controls generated in code, - Code in PL language ;)

## Table of contents
* [Code]
* [Pictures](#Pictures)
* [Technologies](#Technologies)
* [Usage](#TUsage)


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
Pictures are added to the folder of the project, by "Directory" class there is possible to read the location of these pictures.

![GenerujCell](https://user-images.githubusercontent.com/98419600/235795938-7f17c4c4-a8e9-48ae-acf3-cd89d9d4f07a.png)

By code above we can generate the cells on grid. We can add the Cells to the Panel, and then "push" the size of Panel by the width and height of controls.
We set the margin for readability,
Also the function is added to the event On Click of the control. Nothing simpler!

![PanelGrid](https://user-images.githubusercontent.com/98419600/235795945-146624a3-6491-496b-b269-d1431791ee67.png)

Code that generates Panel and adds it to the Main Form window.



#Technologies

C# WFA


#Usage

For proper using project :
Download C&C.rar file -> Open project in VS -> Open Solution Explorer (CTRL + w,s) -> FormaKolkoIKrzyzyk view on solution explorer -> F7 in the view of Form for open the code/ F5 to run the game!


ENJOY!


