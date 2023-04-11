DESCRIPTION OF PROJECT:
This project consists of three games:
1.Maze game

2.Rock paper scissor

3.Memory game using led bulbs


MAZE GAME 
CIRCUIT DIAGRAM :

![image](https://user-images.githubusercontent.com/129647350/231184197-8c98423d-69e5-4914-b1c9-e3fcae8b0770.png)

The components used are a joystick module ,two servo motors and a mini bread 
board. After interfacing the components with arduino board the two servo motor 
are attached with a double tape in such a way that arm of one motor is attached 
to body of another then a Maze is attached with the arm of the second motor. 
The servo motors control the movement of Maze board along x and y directions 
based on the input to arduino board from joystick module. Without touching the 
maze physically we can play with it using joystick module by moving it left and 
right , front and back

ROCK PAPER SCISSOR:
Rock paper scissor is played by two players but for a change our microcontroller 
with replace opponent of the player

![image](https://user-images.githubusercontent.com/129647350/231187390-021dcf99-cbf1-43de-89fb-610029b6d41b.png)

Microcontroller will become the opponent of the player with the help of an 
ultrasonic sensor and three servo motors .Three servo motors are attached with 
cardboard pieces having pictures of rock , paper and scissor . Ultrasonic sensor 
will detect the hands of the player if they are in the range of it and gives input to 
arduino board which will give output to any of the servomotors (the servo motor 
is randomly selected).

MEMORY GAME USING LEDS
Circuit diagram:

![image](https://user-images.githubusercontent.com/129647350/231187709-fc657deb-f4bd-458a-aca4-6e5652305b41.png)

The game circuit uses 4 LEDs and 4 push buttons. As soon as the game turns on, 
all the LEDs blink 4 times and then the game begins.
The Arduino blinks a random led first, then the user is required to immediately 
press the corresponding button, if the button is correct then the Arduino blinks 2 
leds randomly, and this continues until the user presses the buttons in the wrong 
sequence.
Once the user presses the wrong sequence, all the leds blink at high speed, then 
the right sequence is shown, after which the game restarts.

Complete Circuit diagram:

![image](https://user-images.githubusercontent.com/129647350/231188035-f91e7cb3-45ce-45db-ad16-72d035a35add.png)

