This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

## What's this?

This exercise is a change for you to show off your React know-how. The task is to implement a tick-tack-toe
game to decide the Star Wars - Star Trek feud for all time. You can see an example solution of the application
in the gif that is contained in the main page when you run the app for the first time.

## Requirements

The stylistic solutions are up to you, but here are the technical requirements for the project. Remember, you
should show your mastery of React here, so keep that in mind when designing the solution.

### Spicy tic-tac-toe squares

Generate the tic-tac-toe squares based on the current player - Star Trek squares should be Star Trek themed,
and vice versa. Use these APIs [APIs here] to fetch changing content for the squares.

### Spatial tic-tac-toe

Implementing simple tic-tac-toe is simple enough, but since we are dealing with space here, we should play
spatial tic-tac-toe. Your tic-tac-toe should be played on a surface of a Torus (see
[here](http://mathforum.org/library/drmath/view/55291.html)) for an explanation. The grid size should be
selectable by the user.

Of course you should detect when the game ends and who wins, and offer to start a new game.

#### Bonus game related points

Smaller bonus - stor the game history and display which side is winning in the long run.

Bigger bonus - make the games rewindable.

### Regenerating components

Every component needs to have the ability to regenerate - in other words, if there is an error inside a component, there
should be a way for the component to recover to a functioning state without breaking the whole app. You can
see an example of this in the example gif. For convenience, we appreciate a creative way to trigger an error
error in a component to demonstrate this behaviour.

### Tests for critical parts of the application

What are the critival parts of this application? You decide.

## Running the application

You the application should run with just `npm start`. Tests should be run with `npm test`.

## Questions?

Whoever sent you this exercise will answer your questions.