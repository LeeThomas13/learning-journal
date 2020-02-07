# Operators and Loops

### Reading: 

Comparison and logical operators: 150-151, 156, and 157

for and while loops: 170 - 173, and 176

### Comparison Operators

==   Is equal to

!=      Is not equal to

/===       Strict equal to

!==     strict not equal to

/>       Greater Than

/<       Less Than

/>=     Greater Than or Equal to

/<=         Less than or equal to

Structuring Operators

(score >= pass)


((score1 + score2) > (highScore1 + highScore2))


#### __*Example*__



var score1 = 90;            // Round 1 score

var score2 = 95;            // Round 2 score

var highScore1 = 75;        // Round 1 high Score

var highScore2 = 95;        // Round 2 high Score

//Check if scores are higher than current high scores

var comparison = (score1 + score2) > (highScore1 + highScore2);

// Write the message into the page

var el = document.getElementById('answer')

el.textContent = 'New high score: ' + comparison;

### __Logical Operators__

&&      Logical And

||      Logical Or

!       Logical Not

## __Loops__

loops check a condition. it it returns __true__ a code block will run. The then condition will be checked again and if it still returns __true__, the code block will run again. It repeats until the condition returns __false__. 

use selectors:

for

while

do while


[Home Page](https://leethomas13.github.io/learning-journal/)
