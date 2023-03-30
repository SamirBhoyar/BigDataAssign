## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
=> Python is a general-purpose language, meaning it can be used to create a variety of different programs and isn't specialized for any specific problems.
 This versatility, along with its beginner-friendliness, has made it one of the most-used programming languages.

Q2. Why is Python called a dynamically typed language?
=> Dynamic typing means that the type of the variable is determined only during runtime.
Python is dynamically typed language as we do not need to specify any datatype while declaring any variable. This is taken care internally in python.

Q3. List some pros and cons of Python programming language?
=>
Pros:
	-Beginner-friendly
	-Flexible and Extensible
	-Extensive Libraries
	-Highly Scalable
	-Embeddable
	-Portable
cons:
	-Slower than compiled languages
	-Security
	-High memory consumption
	-Dynamically-typed language
	-Complex multithreading
	-Garbage collection leads to potential memory losses

Q4. In what all domains can we use Python?
=> Employing python allows the user to work on multiple domains ranging from Data Science,Machine Learning, Deep Learning, Artificial Intelligence,
 Scientific Computing Scripting, Networking, Game Development to Web Development.

Q5. What are variable and how can we declare them?
=> Variables are containers for storing data values and Python has no command for declaring a variable.
A variable is created the moment you first assign a value to it.

Q6. How can we take an input from the user in Python?
=> input(): This function first takes the input from the user and converts it into a string.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
=> String

Q8. What is type casting?
=> The conversion of one data type into the other data type is known as type casting in python or type conversion in python. 
Python supports a wide variety of functions or methods like: int(), float(), str(), ord(), hex(), oct(), tuple(), set(), list(), dict(), etc. for the type casting in python.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
=> we can take more than one input from the user using single input() functionUsing with help of split() method,
split() method:
This function helps in getting multiple inputs from users. It breaks the given input by the specified separator. If a separator is not provided then any white space is a separator.

Q10. What are keywords?
=> Keywords are some predefined and reserved words in python that have special meanings.

Q11. Can we use keywords as a variable? Support your answer with reason.
=>The keyword cannot be used as an identifier, function, and variable name because Keywords are some predefined and reserved words in python that have special meanings. 

Q12. What is indentation? What's the use of indentaion in Python?
=>Indentation refers to the spaces at the beginning of a code line. The indentation in Python is very important and use to indicate a block of code.

Q13. How can we throw some output in Python?
=> The basic way to do output is the print statement. To end the printed line with a newline, add a print statement without any objects. 
This will print to any object that implements write(), which includes file objects.

Q14. What are operators in Python?
=> In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands.

Q15. What is difference between / and // operators?
=> difference between / and // operators is
/ is regular division(returns float) and // is floor division(returns int).

Floor division was introduced in python 3.

eg:
x = 5/2 #2.5 
y = 5//2 #2

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
=>
str='iNeuron'
print('output=',str*4)

output= iNeuroniNeuroniNeuroniNeuron

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
=>num = int(input('Enter num'));
result =num%2
if result==0:
    print("Entered Number is even",num)
else:
    print("Entered Number is odd",num)

output=>
Enter num6
Entered Number is even 6

Enter num13
Entered Number is odd 13

Q18. What are boolean operator?
=> They connect your search words together to either narrow or broaden your set of results. The three basic boolean operators are: AND, OR, and NOT.

Q19. What will the output of the following?
```
1 or 0 => 1

0 and 0 => 0

True and False and True => False

1 or 0 or 0 => 1
```

Q20. What are conditional statements in Python?
=>Conditional statements are also called decision-making statements. We use those statements while we want to execute a block of code when the given condition is true or false.
ex: Equals: a == b.
Not Equals: a != b.
Less than: a < b.
if-else statement.

Q21. What is use of 'if', 'elif' and 'else' keywords?
=> 'if', 'elif' and 'else' are conditional statements that provide you with the decision making that is required when you want to execute code based on a particular condition. 

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
=> 
age = int(input("What is you age?"))

if age>18:
    print("You can vote")
else:
    print("you can't vote")

Output:
What is you age? 26
You can vote

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```