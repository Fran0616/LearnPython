The Magic 8-Ball is a popular toy developed in the 1950s for fortune-telling or advice seeking.

Write a magic8.py Python program that can answer any “Yes” or “No” question with a different fortune each time it executes.

We’ll be using the following 9 possible answers for our Magic 8-Ball:

```
Yes - definitely. 
It is decidedly so.
Without a doubt.
Reply hazy, try again.
Ask again later.
Better not tell you now.
My sources say no.
Outlook not so good.
Very doubtful.
```

Task 
=
1. In magic8.py, declare a variable name and assign it to the name of the person who will be asking the Magic 8-Ball.
2. Next, declare a variable question, and assign to a “Yes” or “No” question you’d like to ask the Magic 8-Ball.
3. We want to store the answer of the Magic 8-Ball in another variable, which we’ll call answer. For now, assign this variable to an empty string.
4. In order for the answer to be different each time we run the program, we will utilize randomly generated values.
5. In Python, we can use the .randint() function from the random module to generate a random number from a range. But first, let’s import this module so we can use its functions. Add this line of code to the top of magic8.py: `import random`
6. Next, we’ll create a variable to store the randomly generated value. Declare a variable called random_number, and assign it to the function call: `random.randint(1, 9)` which will generate a random number between 1 (inclusive) and 9 (inclusive). Next, add a print() statement that outputs the value of random_number, and run the program several times to ensure random values are being generated as expected. Once you’re sure this is working as we expected, feel free to comment out this print() statemen
