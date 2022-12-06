# Prospecta_Asssignment

Question 2:

Suppose you have a CSV file with the data below.

A1: 5, A2: 7, A3: 9, B1: 3, B2: 8, B3: =4+5, C1: =5+A1, C2: =A2+B2, C3: =C2+B3


1)

1. How will you tackle the challenge above?
  For solving this problem I will take one arrayList and store the input in arrayList separated by comma's and then run loop over arrayList and check the first letter is character than it will the column and if it is Integer than it will be the value of row so we only have to process the Integer for calculate the sum. If String Contains some operator so we will do calculation of it so all these things we store in particular row and column which we had already been got froom ArrayList so this way we will solve this problem.

2.  What type of errors you would you check for?

  I will check for numberformat exception bad operant type errors and taking care of that and solve the problem.
  
 3.  How might a user break your code?

    By Passing first word as a integer which is irrelevant type of data.
