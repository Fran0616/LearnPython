# LearnPython
Python is a general-purpose, versatile and popular programming language. 

Boolean Variables Task 
=
1. Create a variable named my_baby_bool and set it equal to "true".
2. Check the type of my_baby_bool using type(my_baby_bool). You’ll have to print it to get the results to display in the terminal.
2. Check the type of my_baby_bool using type(my_baby_bool). You’ll have to print it to get the results to display in the terminal.
3. It’s not a boolean variable! Boolean values True and False always need to be capitalized and do not have quotation marks.
4. Check the type of my_baby_bool_two and make sure you successfully created a boolean variable. You’ll have to print it to get the results to display in the terminal.


BoolScript.py
=

```
my_baby_bool = "true"
print(type(my_baby_bool))
my_baby_bool_two = True
print(type(my_baby_bool_two))
```

If Statement 
=
The IF statement is a decision-making statement that guides a program to make decisions based on specified criteria. The IF statement executes one set of code if a specified condition is met (TRUE) or another set of code evaluates to FALSE.

If Statement Task
=
1. In script.py, there is an `if` statement. I wrote this because my coworker Dave kept using my computer without permission and he is a real doofus. If the `user_name` is Dave, it tells him to stay off my computer. Enter a user name in the field for `user_name` and try running the program.
2. Oh no! We got a `SyntaxError!` This happens when we make a small error in the syntax of the conditional statement. Read through the error message carefully and see if you can find the error. Then, fix it, and run the code again.
3. Ugh! Dave got around my security and has been logging onto my computer using our coworker Angela’s user name, `angela_catlady_87`. Set your `user_name` to be `angela_catlady_87`. Update the program with a second if statement so it checks for Angela’s user name as well and prints "I know it is you, Dave! Go away!"
in response. That’ll teach him!

IfScript.py
=
```
# Enter a user name here, make sure to make it a string
user_name = "angela_catlady_87"

if user_name == "Dave": #syntax error because of one equal sign
  print("Get off my computer Dave!")
if user_name == "angela_catlady_87":
  print("Get off my computer Dave!")
```

Relational Operators II
=

Now that we’ve added conditional statements to our toolkit for building control flow, let’s explore more ways to create boolean expressions. So far we know two relational operators, equals and not equals, but there are a ton (well, four) more:

- > greater than
- >= greater than or equal to
- < less than
- <= less than or equal to

Relational Operators II Task 
= 
1. Create an `if` statement that checks if `x` and `y` are equal, print the string below if so: `"These numbers are the same"`
2. The nearby college, Calvin Coolidge’s Cool College (or 4C, as the locals call it) requires students to earn 120 `credits` to graduate. Write an `if` statement that checks if the student has enough credits to graduate. If they do, print the string:

RelationalOperatorsscript.py
```
x = 20
y = 20

# Write the first if statement here:

if x == y:
  print("These numbers are the same")


credits = 120

# Write the second if statement here:
if credits >= 120:
  print("You have enough credits to graduate!")
```
