# games50-projects-2018-x-pong

## Task:
Take the Pong example we covered in class and extend it in a small but fun way by giving one of the paddles (or perhaps both) logic for playing the game so that you don’t always need a buddy to play the game with you! 

Implement an AI-controlled paddle (either the left or the right will do) such that it will try to deflect the ball at all times. Since the paddle can move on only one axis (the Y axis), you will need to determine how to keep the paddle moving in relation to the ball. 

Currently, each paddle has its own chunk of code where input is detected by the keyboard; this feels like an excellent place to put the code we need! Once either the left or right paddle (or both, if desired) try to deflect the paddle on their own, you’ve done it!

## My idea for a solution:
I'll want to predict the trajectory of the ball, and move the paddle there within the time limit!

#### Simpler Aproach
Although if the ball is a constant speed, it may just be simpler to have the paddel follow the Y level of the ball.

#### Result:
I ended up implementing both! Player 1 predicting the trajectory, and Player 2 naively tracking the ball.

# Version of love used: 
LOVE 11.5 (Mysterious Mysteries)

# Upon completion
Submit to https://submit.cs50.io/courses/33