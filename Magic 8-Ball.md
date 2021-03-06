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
4. In order for the answer to be different each time we run the program, we will utilize randomly generated values. In Python, we can use the .randint() function from the random module to generate a random number from a range. But first, let’s import this module so we can use its functions. Add this line of code to the top of magic8.py: `import random`
5. Next, we’ll create a variable to store the randomly generated value. Declare a variable called random_number, and assign it to the function call: `random.randint(1, 9)` which will generate a random number between 1 (inclusive) and 9 (inclusive). Next, add a print() statement that outputs the value of random_number, and run the program several times to ensure random values are being generated as expected. Once you’re sure this is working as we expected, feel free to comment out this print() statement
6. Now that we’ve declared all the variables needed, it’s time to implement the core logic of our program! For this section, we’ll be utilizing control flow using an if/elif/else statement to assign different answers for each randomly generated value. First, write an if statement where if the random_number is equal to 1, answer is assigned to the phrase “Yes - definitely.” 
7. Next, write an elif statement after the if statement where if the random_number is equal to 2, answer is assigned to the phrase “It is decidedly so”. Then, continue writing elif statements for each of the remaining phrases for the values 3 to 9. Recall that the 9 possible answers of the Magic 8-Ball are:
- Yes - definitely.
- It is decidedly so.
- Without a doubt.
- Reply hazy, try again.
- Ask again later.
- Better not tell you now.
- My sources say no.
- Outlook not so good.
- Very doubtful.
8. Following the if/elif statements, add an else statement that will set answer to the string “Error”, if the number was accidentally assigned a value outside of our range.
9.  Now, let’s see our program in action! Write a print() statement to output the asker’s name and their question
10.  Add a second print() statement that will output the Magic 8-Ball’s answer


Code
=
```
import random
name = "Francisco"
question = "Will my record sell?"
answer = ""
random_number = random.randint(1,9)

if random_number == 1:
  answer = "Yes - definitly."

elif random_number == 2:
  answer = "It is decidedly so."

elif random_number == 3:
  answer = "Without a doubt."

elif random_number == 4:
  answer = "Reply hazy, try again."

elif random_number == 5:
  answer = "Ask again later."

elif random_number == 6:
  answer = "Better not tell you now."

elif random_number == 7:
  answer = "My sources say no."

elif random_number == 8:
  answer = "Outlook not so good."

elif random_number == 9:
  answer = "Very doubtful."
else:
  answer = "Error."

print(name, "asks:", question)
print("Magic 8-Ball\'s answer:", answer)

```

Test Data
= 
```
Francisco asks: Will my record sell?
Magic 8-Ball's answer: Outlook not so good.
```

```
Francisco asks: Will my record sell?
Magic 8-Ball's answer: It is decidedly so.
```
