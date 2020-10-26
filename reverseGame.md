<p align="center">
  <h3 align="center">Reverse Game</h3>

</p>

<br>

## Table of contents
- [About the Project](#about-project)
- [User Flow](#)
- [Challenge To Do List](#)


<hr>

## about project

This is a reveal game where a user inputs a word and it reverses for them and tells them whether the input is reversable or not.
<hr>

## User Flow

This is the expected output as you run your program:

`GoodMorning` - Depending on time of day

`what is your name?:` say the user says `username`

`Thank you username`

`Are you :`

    * male(m)

    * female(f)

    * do not wish to disclose (d)?

    Please provide the reply here:`

Use the following greetings depending on what the user says:

    * `f` - it will say `Lady` as in `Thank you Lady username`

    * `m` - it will say `Mr.` as in `Thank you Mr. username`

    * `d` - It will say  nothing as in `Thank you username!We respect your right to not tell us.`

then

    To proceed in the game choose an option:
        a. Play
        b. Learn the rules

If user selects a:

 `Welcome to the reverse Game:
 Please enter a word to continue:`

-  If the user enters a letter:

    `Please input a word and not a letter`

-  If the user enters nothing/ Presses Enter / Space:

    `You did not enter anything. Please input a word!`


If user selects b:

    Hey there username! Here are the rules username:
     1. Enter word that you think can be read forwards and backwards
     2. if it is correct you will score 1 point.
     3. If it is wrong you get 0 points.

where `username` is the name they entered at the top.

If user selects a:

    welcome to reverseGame username, please enter a word that you think is reversible:

If the user gets the answer right:

    You are correct username! You scored 1 point. Do you want to play again?

If the user gets the answer wrong:

    OOps username! That is wrong! You scored 0 points. Do you want to try again?

after these, it should take the user back to the play menu




Then picks the greeting
## Challenge To Do List
Check for the following features:

- [ ] Check that the user inputs are NOT blank.
- [ ] Check that the user inputs are different and tell them.
- [ ] Greeting should match the time of day.
- [ ] Add the words
