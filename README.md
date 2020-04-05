# Grapher-VGA-Graphing-Calculator-

## Description: 
Grapher is a graphing calculator application that allows users to graph lines, polynomials of power 2, polynomials of power 3, polynomials of power 4, square root functions, and exponential functions. The project targets a DE1-SoC board. This project was done in a group of 2 for a Computer Organization course (ECE243) at the University of Toronto.

## Project Run-through: 

1.	To view the project on CPULATOR (https://cpulator.01xz.net/?sys=arm-de1soc), set preallocated memory in CPULATOR to 16 MB and disable device-specific warnings in CPULATOR. 
3.	Upon running the application, the following display will appear.
    <p>
        <img src= "Images/Screen 1.png" width="260" height="240") />
    </p>
4.	After pressing KEY[0] to continue, the following screen will appear.
    <p>
        <img src= "Images/Screen 2.png" width="260" height="240") />
    </p>
5.	Use the switches to choose the function to graph. The selection is NOT in binary. The first option is selected with SW[0], the second option will be selected with SW[1] and so on. 
6.	If for example the user chooses to graph a linear polynomial, the following screen will appear. The user can select values for A, B and C with switches in binary. First the user chooses A, then B, and then C. After setting the switches to the value the user wants for a variable, the user must press KEY[0] to set the next variable. The user can select negatives values, to do so the user must set SW[9] to one then input the magnitude on SW[8:0].
    <p>
        <img src= "Images/Screen 3 - a.png" width="260" height="240") />
    </p>
7.	After selecting each variable, the display updates to display the chosen values in the bottom right corner. The following screen shows what appears when the user has chosen A and B for a linear polynomial.
    <p>
        <img src= "Images/Screen 3 - b.png" width="260" height="240") />
    </p>
8.	Once the user has chosen all variables, the function will be graphed. 
    <p>
        <img src= "Images/Screen 4 - single.png" width="260" height="240") />
    </p>
9.	The user can see the equation for the function graphed in the bottom right corner. In the top left corner, the user can see the options for what to do next. The user can exit the application by pressing KEY[3]. To reset the graph, the user can press KEY[0], the user will be prompt back to the selection of functions to graph another, without the previously displayed graph. To add another graph to this display, the user must press KEY[2]. The user will be prompt back to the selection, after inputting the variables for the graph, the new graph will be added to the display, like shown in the image below. A maximum of 20 graphs can be displayed at the same time. 
    <p>
        <img src= "Images/Screen 5 - multiple.png" width="260" height="240") />
    </p>
 
