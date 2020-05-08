# Perl_Tictactoc

    Tictactoc game build in Perl for Holberton's Hackday.

## **What about Perl**

 Practical Extracting and Reporting Languaje. Is programming language originally developed in 1987 as a general-purpose Unix scripting language; it can be used in a variety of tasks, you can use perl for extracting information from a text file and printing out a report, converting a text file into another form or number of problems as system programming.

Perl is implemented as an interpreted language; it includes the capacity to execute large sets of commands, because it combines it combines features of languages like C with shell script’s.

In Perl you don't have to specify the data type of a variable.

Here you can see a simple print sentence:

    print “Hello, world\n”;
    Output:Hello, world

Also a simple variable declaration:

    $str=”My name is The Machine”;
    print “$str\n”;
    Output: My name is The Machine

## **How to play**

You have to type the usage command to start the game:
    user@ubuntu:~/Perl_Tictactoc/Perl_Tictactoc$ perl game

    ┌───┬───┬───┐
    │ 1 │ 2 │ 3 │
    ├───┼───┼───┤
    │ 4 │ 5 │ 6 │
    ├───┼───┼───┤
    │ 7 │ 8 │ 9 │
    └───┴───┴───┘
    X's move?:

You have to select the position to put de "X" character and tip the number and prees Enter.
Then, the number is replaced for the "X and "the game will ask "O's" position.

    ┌───┬───┬───┐
    │ 1 │ 2 │ 3 │
    ├───┼───┼───┤
    │ 4 │ X │ 6 │
    ├───┼───┼───┤
    │ 7 │ 8 │ 9 │
    └───┴───┴───┘
    O's move?:  


As a player, you have to do this till the game is over.

    ┌───┬───┬───┐
    │ X │ X │ O │
    ├───┼───┼───┤
    │ 4 │ X │ O │
    ├───┼───┼───┤
    │ 7 │ 8 │ O │
    └───┴───┴───┘
