# Shift-Coding-Challenge
This is a code of a solution that has the most impact on my entire software development career.

## What is a shift code?
* A shift code is where a message can be encoded (and decoded) simply using python. This is done by moving the characters forwards through the alphabet by a certain number of letters. For example, encoding "winner" would be "xjoofs" when the code is "shifted" by one.

## Solving the Problem
* Firstly, a collection of the alphabet is stored as a single list. This list will contain another character which is "space" to allow for the code to encode and decode messages with spaces. This bring a total of 27 characters.
* This code prompts the user to pick a number (betwee 1 and 27) which will do the necessary coding. However, say for instance a user wants to encode the message "xyz", and select 7 as a shift number, the shift will make the letters go past the alphabets and count "space" as it is part of the characters of the list. This could lead to a coding error.
* This can be solved by reading in the contents of the list and then identifying the alphabets. A restriction of making the shift return back to the first letter of the alphabet when it reaches the end. In this case it will result in "efg".




