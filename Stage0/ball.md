# ball()

## Feature

- It contains the original x and y coordinates of the ball
- It updates the coordinates of the ball during the game play
- It changes the direction of the ball after hitting the paddle
- Responsible for the movement of ball

## Acceptance Criteria

### Scenario: Set the ball coordinates

  Given: The settings are done
  
  When: The game starts
  
  Then: Initialize the ball coordinates to middle of the screen

### Scenario: Change in the direction of the ball

  Given: The game is going on

  When: The ball hits any one of the paddles

  Then: Change the direction of the ball using random function
