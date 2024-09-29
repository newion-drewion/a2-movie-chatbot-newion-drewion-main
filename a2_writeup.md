# Assignment 2 - Write UP

## Description
This assignment is about learning and applying the while loop and iterating through multiple lists at a time.  We also will discuss how we match things in chatbots in order to extract what a user is trying to find.  Next assignment we will work with data bases and how we can extract information from them.

## What to complete
1. Go through the notes.py file w/ Mr. Berg
2. Complete `a2.py`, Mr. Berg will walk everyone through the process
3. Make sure you pass all asserts in `a2.py`
4. Complete the reflection problems below
5. Push your code to github for grading

## Reflection Questions
1. What was difficult for you while completing the match function?

The part when the pattern had %, just because it took an extra "container" variable for words from source matched by %. Also, the .strip method was new for me. 

2. Explain how you could use the match function for extracting information from a movie database.

We can change x, y, and z to be strings of movie information that gets output depending on % and _, which could be changed to the user's input depending on what format they write the message in. 

For example, the source could be sometihng like ["The Martian", "Matt Damon", "2015"] and the pattern could be an input like ["%", "Matt DAmon", "%"].

