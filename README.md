Find Non Repeating Characters
The string is a combination of characters when 2 or more characters join together it forms string whether the formation gives a meaningful or meaningless output. In python programming, we treat a single character also as a string because there is no datatype as a character in python. In this python program, we will find unique elements or non repeating elements of the string.

Find Non Repeating Characters in python

Algorithm
Step 1:- store the string in a varaible lets say String.
Step 2:- lets it be “prepinsta”.
Step 3:- Start iterating through string.
Step 4:- Initialize count variable.
Step 5:- Again start iterating through same string.
Step 6:- Increment count variable as character is found in string.
Step 7:- If count is more then 2 break the loop.
Step 8:- If count is 1 print the character.
Step 9:- End.
Python Code:- Find Non Repeating Characters
#take user input
String = "prepinsta"
for i in String:
    #initialize a count variable
    count = 0
    for j in String:
        #check for repeated characters
        if i == j:
            count+=1
        #if character is found more than 1 time
        #brerak the loop
        if count > 1:
            break
    #print for nonrepeating characters
    if count == 1:
        print(i,end = " ")
Output
r e i n s t a
