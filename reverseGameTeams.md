<p align="center">
  <h3 align="center">Reverse Game with Friends</h3>

</p>

<br>

## Table of contents
- [About the Project](#about-project)
- [User Flow](#)
- [Challenge To Do List](#)


<hr>

## about project

While using the existing reverse game, add the option for a player to join a team and also score points for a team.
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
    Choose a Team that you want to join:
            a. TeamNesh
            b. TeamMalli

                Team Nesh Motto: (Sisi ni watu wale wasee)
                Team Malli Motto: (Sisi ni watu wa alli mingi )

Depending on what the user chooses, it should then say:

        Welcome to {TeamName}! Our Motto is {TeamMotto}


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

    You are correct username! You scored 1 point for {TeamName}.
    Do you want to:
        a. Play again?
        b. Exit the game?

If the user gets the answer wrong:

    OOps username! That is wrong! You scored 0 points for {TeamName}.
    Do you want to:
        a. Try again?
        b. Exit the game?

If the user selects `a` it should take the user back to the play menu


If the user selects `b` it should tell them:
    `Thank you username for playing Reverse Game as a memeber of {TeamName}.
        {TeamName} now has Z points.
    Come back again and play.`

        Where Z is the total score of the game.

The game should be able to add and update the points form the DB.

