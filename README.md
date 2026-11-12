# ArduinoSemesterAssignment

**Concept: what your object does and for whom (max. 150 words).**  
My project will be a game-style reaction timer, with two types of reaction timers.   
In the beginning, the screen will show short instructions: either press the button or move the joystick to select which game you would like to play. Once a game is selected, press the button to indicate you are ready.  
The first will be a basic reaction timer, where a light will go from green (ready to begin) to yellow (game started) to red (press button to record reaction time).  
The second will also be a reaction timer, but instead of there being one input, the button, there will be four possible options: Up, Down, Left, or Right (UDLR). One of these corresponding letters will be displayed on the 1-digit 7-segment display, and when it is displayed the user will need to move the joystick in the associated direction.  
Each of these will record the reaction time, and it will display "You reacted in __ms," and some sort of grade: "needs some work", "okay", "decent", "good", "amazing!", or "INSANE!!"  

**Your tier.**  
2

**Which live statistics you calculate and why they are useful for your user.**  
The milliseconds will be recorded between when the light or screen changes, depending on the game selected, and a grade will be given based on this number.

**How to run it (libraries, COM port, Node-RED nodes).**

**Process & reflection (max. 1 page): your plan vs. what actually happened, the biggest problem and how you solved it, what you would do differently, and which sources or tools you used.**
