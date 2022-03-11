Memory simulator
Authored by Christopher Haj
207824772

==Description==

This program creates a database of type .txt in which it saves all string sequences (with a limit of 510 characters in each request)
and after the first run of the program, it will keep updating the contents of the database with the input provided by the user in each run.

There are two special key-words in this program for specific commands, "history" and "exit", the former is used to provide all content
saved in the database, while latter is used to stop the execution of the program.


==Program Files==
main.c
file.txt (created by program after first run)


==How to compile?==
compile: gcc main.c -o ex1
run: ./ex1


==Input==
Input is passed in by the user with a max of 510 characters and can be of three types.
1) When Key-word ("exit") is entered the program terminates and stops running.
2) When Key-word ("history") is entered the program goes through the database of entered words and prints them all in order.
3) When other string sequences are entered, they get saved in the database.


==Output:==
When entering type (3) of Input, the program prints out the amount of letters and words that were in the string sequence.
Keyword ("history") prints out everything that was saved inside the database ("file.txt") in numbered order.

