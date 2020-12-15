# rockPaperSciz
Rock Paper Scissors game made with Javascript 


Uses Javascript functions to give the computer random logic allowing it to play against you.

Runs confetti.js during victory as animation.

Groups choices and what wins over what inside an object.

Reset function to set after each match by clicking any item.

Score reset function.

Uses Math.random to give logic to computer = 

```javascript
function computerRandomChoice() {
  const computerChoiceNumber = Math.random();
  if (computerChoiceNumber < 0.2) {
    computerChoice = 'rock';
  } else if (computerChoiceNumber <= 0.4) {
    computerChoice = 'paper';
  } else if (computerChoiceNumber <= 0.6) {
    computerChoice = 'scissors';
  } else if (computerChoiceNumber <= 0.8) {
    computerChoice = 'lizard';
  } else {
    computerChoice = 'spock';
  }
}
```
