# CS2401-Project-One-A-Checkbook-Class-solved

Download Here: [CS2401 Project One: A Checkbook Class solved](https://jarviscodinghub.com/assignment/project-one-a-checkbook-class-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

A checkbook is a container that holds a record of all the checks written by the owner. Our container, being computerized, will off the user a variety of extra features so that they can find, organize and better understand their check-based spending.
Begin by copying into your working directory the files that I have already written for you for this project. They are
• date.h
• date.cc
• check.h
• check.cc
• main.cc
• bob_checks.txt
The check.h and check.cc files define a class called Check, which holds the information for a single check, including the check_number, the date that it was written, to whom it was written and the amount of the check. This class is dependent on the Date class which I have written. You will not be changing anything about the Date class, nor anything about the check.h file. Note that the Date class already has defined the >> and << operators as well as a full set of comparison operators. You will be using these. Do not try re-invent nor circumvent these operators. (e.g. Users will type in dates as 9/6/2017 – not as separate numbers from which you reassemble a date.)
In the check.cc class you will need to write the implementations for the write_check function (an input function) and the output function.
Next you are to create checkbook.h and checkbook.cc files which will consist of an array capable of holding 200 checks, a number to keep track of how full that array is, and a balance, which says how much money is in the checking account. By looking at the main you can see the names of the functions that you are to writing for this account. (The main that I give you is also a file you should not be changing.) These will give the user the ability to:
1. Have their checkbook reloaded from the backup file – so they don’t re-enter their checks everytime they start the program
2. Make a deposit into their checkbook.
3. Write a check – the user can enter the check-number, but there can be no duplicate check-numbers in the checkbook.
4. See the checkbook balance
5. See a listing of all the checks that they have written – for each check they should see all information about that check
6. Remove a check by entering its check-number. That number then becomes available for future checks and the amount is returned to the balance.
7. Sort the checks by check-number
8. Sort the alphabetically by the person to whom they were written
9. Sort the checks by the date they were written
10. Find and view all the checks written to a particular payee along with the total amount of those checks
11. Find the average of all the checks written
12. Have the checkbook backed up to the same file that it was read from at the beginning of the program, upon exiting the program
Note that 2 – 11 of the options listed above are menu options that are done in my main in a loop. The back-up file is done without the user’s knowledge or interaction.
Each file that you create should have a header block with your name, an approximate date and a description of what is done in the file. Also, your container class should exhibit a correct use of the const and static const.
All files, including the ones that I have given you and your own data file, are to be submitted on Blackboard. This project is due at 11:59 on Thursday, September 14th. For each day late there will be a 5% penalty.


