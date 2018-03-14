This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

## What's this?

This exercise is a change for you to show off your React know-how. The task is to implement a tick-tack-toe
game to decide the Star Wars - Star Trek feud for all time. The game is played on the same computer against
your friend with differing opinions. You can see an example solution of the application
[here](https://react-features-exercise.herokuapp.com). The example application showcases the core features
listed below - we expect slightly more polished answer from you, but the focus of the exercise is to use
appropriate React features and provide a solid piece of software. The example solution also is not the
perfect solution, so don't feel obligated to repeat the design choises made there.

You are free to inject any amount of fun you wish to make the reviewers life funnier.

## Requirements

The stylistic solutions are up to you, but here are the technical requirements for the project. Remember, you
should show your mastery of React here, so keep that in mind when designing the solution. You can use npm packages
as you see fit, keeping still in mind that this should show your programming abilities.

### Spicy tic-tac-toe squares

Generate the tic-tac-toe squares based on the current player - Star Trek squares should be Star Trek themed,
and vice versa. You should use an external API to fetch and display some data. The example uses
[GIPHY](https://giphy.com/), and you can use that - API key will be supplied to you by the one who gives you this task.

### Spatial tic-tac-toe

Implementing simple tic-tac-toe is simple enough, but since we are dealing with space here, we should play
spatial tic-tac-toe. Your tic-tac-toe should be played on a surface of a Torus (see
[here](http://mathforum.org/library/drmath/view/55291.html)) for an explanation - Google for more material.
The grid size should be selectable by the user.

Of course you should detect when the game ends and who wins, and offer to start a new game. The example solution
shows the winning squares on green background when the game ends.

#### Bonus game related points

Smaller bonus - store the game history and display which side is winning in the long run. This is implemented
in the example solution

Bigger bonus - make the games rewindable. This is no implemented in the example solution.

### Regenerating components

Every component needs to have the ability to regenerate - in other words, if there is an error inside a component, there
should be a way for the component to recover to a functioning state without breaking the whole app. You can
see an example of this in the example app (the 'Break me' button breaks the component it lives in). For convenience,
we appreciate a creative way to trigger errors in components to demonstrate this behaviour.

### Tests for critical parts of the application

What are the critival parts of this application? You decide.

### Idiomatic React and TypeScript

The core technologies of this exercise are React and TypeScript, and we except you to use them and their features
properly.

## Running the application

The application should run with just `npm start`. Tests should be run with `npm test`. The app should compile without
linting errors and the tests must pass. You can clone this repo and use this as a basis for your application (this implements
`npm start` and `npm test` scripts), or if you prefer other boilerplate, feel free to use that.

Bonus points - deploy your solution in Heroku or other comparable service.

## Returning the assignment

We want to inspect your code, so please deliver the solution as specified by the person who delivers this assignment.

## Questions?

Whoever sent you this exercise will answer your questions.