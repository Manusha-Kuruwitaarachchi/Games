Turtle Racers Game
Overview

Turtle Racers is a fun, interactive Python game where multiple turtles race to the finish line. Players can choose the number of racers, and each turtle is assigned a different color. The race is visually displayed using the turtle module, and the first turtle to reach the finish line is declared the winner.
Features

    Players can select the number of racers (between 2 to 10).
    Each turtle is assigned a unique color from a predefined list.
    Turtles race across the screen in a straight line, with random movement distances to create an element of chance.
    The game uses the turtle module for graphics and tkinter to control the window behavior.

Requirements

    Python 3.x
    turtle module (standard Python library)
    tkinter module (standard Python library)
    random module (standard Python library)

How to Play

    Run the game script.
    Enter the number of racers when prompted (between 2 and 10).
    Watch the turtles race across the screen.
    The winner will be displayed once a turtle reaches the finish line.

Instructions

    Set Up the Game:
        The game initializes the turtle screen with a specified width and height.
        The user is prompted to enter the number of racers.
        The turtle screen is set up with the chosen number of turtles, each with a unique color.

    Start the Race:
        Turtles move forward by a random distance in each step.
        The race continues until one of the turtles reaches the top of the screen.
        The color of the winning turtle is displayed as the winner.

    End the Game:
        After displaying the winner, the game waits for a few seconds before closing.

Customization

    You can change the list of colors in the COLORS list.
    The race track dimensions can be adjusted by modifying the WIDTH and HEIGHT variables.
    The range of random distances turtles move can be adjusted for different race dynamics. 
