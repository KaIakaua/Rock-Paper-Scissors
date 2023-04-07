# Rock-Paper-Scissors

-------------------------------------------
To not put much effort into going back and forth between windows and ubuntu i'll put comments and/or issues here.

1- Line 22 to line 25: after editing the code a bit, I don't need this many console.logs instead they are causing actual problems, delete. Should be something like:

const computerSelection = getComputerChoice(textArray);

console.log(computerSelection + " is the computerSelection");

2- Line 55: function playRound does nothing and it's just a placeholder, I don't really need it there at all right now, delete.
