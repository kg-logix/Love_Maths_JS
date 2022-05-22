# Love Maths Game

This is an interactive web game based on JavaScript.

Participants of this game are presented with a maths challenge which they are required to compute and submit their answer. The website then alerts the user whether or not the naswer was correct. If not, the correct answer is displayed within the alert dialog box such that the participant is informed of the correct answer. 

![Game Design](/assets/images/game_design.png)

# Table of Contents
- [Features](#features-a-id"features-link"a)
    - [Operand Buttons](#operand-buttons-a-id"operand-buttons-link"a)
    - [Score Keeping](#score-keeping-a-id"score-keeping-link"a)
    - [Page Load](#page-load-a-id"page-load-link"a)
- [Testing](#testing-a-id"testing-link"a)
    - [Bugs](#bugs-a-id"bugs-link"a)
    - [Validator Testing](#validator-testing-a-id"validator-link"a)
    - [Unfixed Bugs](#unfixed-bugs-a-id"unfixed-bugs-links"a)
    - [Deployment](#deployment-a-id"deployment-link"a)
- [Credits](#credits-a-id"credits-link"a)
    - [Content](#content-a-id"content-link"a)

# Features <a id="features-link"></a>

## Operand Buttons <a id="operand-buttons-link"></a>
- Beneath the title of the game, the participant finds four large buttons, each representing a mathemathical operator.
- Selecting a buttons changes the challenge to that respective mathematical operator.
- The subtact challenge is designed in such a way that the result is always positive so that the user does not need to include the negative symbol.
- The division challenge is designed in such way that the result is always a positive whole number to avoid long irrational numbers.

![Operand Buttons](/assets/images/operand.png)

## Score Keeping <a id="score-keeping-link"></a>
- At the bottom of the page a score keeping section is included which counts the number of correct and incorrect answers.

![Score Keeping](/assets/images/score_keeping.png)

## Page Load <a id="page-load-link"></a>
- On page load the web game executes two actions. 

- The first being that the default meth operation is chosen, this being the addition operator. 

- Furthermore, the page focuses on the input section of the game such that the participant can immediately enter an asnwer and submit via an enter key press.

# Testing <a id="testing-link"></a>

 - Page was tested to work in different browsers: 
    - Chrome
    - Firefox
    - Safari

- Confirmed that each button triggers its associated challenge and that the submit answer button work correctly.

- At each different operation challenge the game was tested against correct and incorrect answers. 

- The scores at the bottom of the game were checked to be functioning correctly.

## Bugs <a id="bugs-link"></a>

- No bugs have been detected ... yet.

## Validator Testing <a id="validator-link"></a>

- HTML
    - No errors were returned when passing through the official W3C validator.

- CSS
    - No errors were found when passing throught the official (Jigsaw) validator

- Accessibility
    - Confirmed that the colors and fonts chosen are easy to read and accessible by running it through lighthouse in devtools.

## Unfixed Bugs <a id="unfixed-bugs-links"></a>

- No unfixed bugs

# Deployment <a id="deployment-link"></a>

- The site was deployed to GitHub pages.

The live link can be found [here]()

# Credits <a id="credits-link"></a>

## Content <a id="content-link"></a>

The code to make the website was built using a walk-through within an online course.
