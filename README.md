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


Boolean Operators: and Task
= 

1. Set the variables `statement_one` and `statement_two` equal to the results of the following boolean expressions:

- Statement one:`(2 + 2 + 2 >= 6) and (-1 * -1 < 0)`
- Statement two: `(4 * 2 <= 8) and (7 - 1 == 6)`

2. Let’s return to Calvin Coolidge’s Cool College. 120 credits aren’t the only graduation requirement, you also need to have a GPA of 2.0 or higher.

Rewrite the `if` statement so that it checks to see if a student meets both requirements using an `and` statement.

If they do, return the string: `"You meet the requirements to graduate!"`

script.py
```
statement_one = (2 + 2 + 2 >= 6) and (-1 * -1 < 0)

statement_two = (4 * 2 <= 8) and (7 - 1 == 6)

credits = 120
gpa = 3.4

if credits >= 120 and gpa >= 2.0:
  print("You meet the requirements to graduate!")
```


Else If Statements
=
We have `if` statements, we have `else` statements, we can also have `elif` statements. An `elif` statement checks another condition after the previous if statements conditions aren’t met. First, the `if` statement is checked, then each `elif` statement is checked from top to bottom, then finally the `else` code is executed if none of the previous conditions have been met.

Task 
=
1. Calvin Coolidge’s Cool College has noticed that students prefer to get letter grades. Write an if/elif/else statement that:
- If grade is 90 or higher, print "A"
- Else if grade is 80 or higher, print "B"
- Else if grade is 70 or higher, print "C"
- Else if grade is 60 or higher, print "D"
- Else, print "F"


Code.py
```
grade = 86

if grade >= 90:
  print ("A")
elif grade >= 80:
  print("B")
elif grade >= 70:
  print("C")
elif grade >= 60:
  print("D")
else:
  print("F")

if grade >= 90:
  print("A")
elif grade >= 80:
  print("B")
elif grade >= 70:
  print("C")
elif grade >= 60:
  print("D")
else:
  print("F")
```

Sumamry
= 
In the `code.py` example above each condition is checked sequentially and only prints one message, the code is completed when one of the condition has bet met, if the code gets through all the elif statement all no condtion was met then the else code is executed. 
