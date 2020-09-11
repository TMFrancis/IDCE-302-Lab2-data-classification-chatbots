- Name: Tom Francis
- Date created 10 September 2020
- Description: Lab 2 involves two scripts. Both employ user input. The first classifies input data: soliciting input on the temperature and characterizing the temperature as one of four general ranges. 

You should edit your README file to provide the following information:
- Summarize what your scripts do, or the problem you were trying to solve.
- Summarize any major errors or difficulties you encountered and what sources you used to resolve them.
- If you could resolve an issue, give as much detail as you can about what the issue was, and what sources you looked at to try and figure something out.

Remember that you are encouraged to look for answers online! Stackoverflow, other Github repositories, or Python documentation are all good places to start.

## Script 1 - Classifying Data
Write a function, called “feelTemp”, that converts a given temperature (in Fahrenheit) into four categorical levels, hot, warm, cool, and cold using the following criteria:

- If the temperature is 100 or above, the functions return “It is hot.”;
- If the temperature is between 70 and 100, the function returns “It is warm.”;
- If the temperature is between 32 and 70, the functions return “It is cool.”;
- If the temperature is below 32, it returns “It is cold.”

The function feelTemp will take one value for the temperature, and then returns a category as a string. When running the program, the user is prompted to input a temperature, then the program prints one of the four categorical levels (hot, warm, cool, and cold) that the given temperature falls into.

Use `if/elif/else` structure to classify the input numerical values into one of the four categories; use the input to get input from the keyboard. Be sure to include comments and documentation in your script to tell me what it’s doing!

## Script 2 - Create your first chatbot!

The internet is full of amazing "intelligent" [chatbots](https://en.wikipedia.org/wiki/Chatbot) that use things like [neural networks](https://arstechnica.com/science/2019/12/how-neural-networks-work-and-why-theyve-become-a-big-business/) to talk like a certain person: many of these chatbot applications are written in Python. Simple chatbots follow [decision trees](https://www.dummies.com/programming/python/using-nested-decision-statements-python/) by looking for specific keywords using things like `if, elif, else` statements. Some chatbots may use `input()` to capture input from a user, including numbers.

Write a chat bot that *either* uses `if, elif, else` to respond back to the user *or* collects a number from the user then employs [type conversion](https://www.digitalocean.com/community/tutorials/how-to-convert-data-types-in-python-3) to change the number (remember that `input()` only returns string values) and perform some sort of computation. 

If you're feeling really motivated, you can write a script that combines the two. A good first step is to write out a "script" for the user and the program. For example: 

**Sample script for `input` chatbot**
- Computer: "Hi, what's your name?"
- User: "Pat"
- Computer: "Hi Pat. How old are you?"
- User: "20"
- Computer: "Pat, in ten years you'll be 30."

**Sample script for `if, else, elif` chatbot**
- If the function is run using the name `Shadrock` as an argument the computer will display: "Hey, Shadrock!"
- If the function is run using the name `Shashank` as an argument the computer will display: "Hi, Shashank!"
- ... or `else` if the function is run using another `name` the computer will display "Hi, `name`. I don't believe we've met yet."

Once you know what you want the inputs and outputs of your code to be, based on the script, you can start. 
Happy coding!
