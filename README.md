# Perl_Tictactoc

    Tictactoc game build in Perl for Holberton's Hackday.

##Usage

$ perl FILENAME

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


user@ubuntu:~/Perl_Tictactoc/Perl_Tictactoc$ perl game.pl

        Player 1 (✿) v/s Player 2 (♥)

                             
                    |   |    
                  7 | 8 | 9  
                 ___|___|___ 
                    |   |    
                  4 | 5 | 6  
                 ___|___|___ 
                    |   |    
                  1 | 2 | 3  
                    |   |    

              Player 1's turn: 

You have to select the position to put dePlayer 1 (✿) and tip the number and prees Enter.
Then, the number is replaced for the "✿" and "the game will ask "Player 2 (♥)'s" position.

        Player 1 (✿) v/s Player 2 (♥)

                             
                    |   |    
                  7 | 8 | 9  
                 ___|___|___ 
                    |   |    
                  4 | ✿ | 6  
                 ___|___|___ 
                    |   |    
                  1 | 2 | 3  
                    |   |    

              Player 2's turn: 


As a player, you have to do this till the game is over for example:

        Player 1 (✿) v/s Player 2 (♥)

                             
                    |   |    
                  7 | 8 | ♥  
                 ___|___|___ 
                    |   |    
                  4 | ✿ | 6  
                 ___|___|___ 
                    |   |    
                  1 | 2 | 3  
                    |   |    

              Player 1's turn: 

like this until some player wins:

        Player 1 (✿) v/s Player 2 (♥)

                             
                    |   |    
                  ✿ | 8 | ♥  
                 ___|___|___ 
                    |   |    
                  4 | ✿ | 6  
                 ___|___|___ 
                    |   |    
                  ♥ | 2 | ✿  
                    |   |    

           Player 1 is the winner!
