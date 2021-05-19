# Python
## Python installation 3.7 or above
### Pycharm set up
#### Documentation with README.md to store on Git-hub

- Testing the python env `print("Welcome to Engineering 88!")`
#### What is Python and how does it link to DevSecOps
- Easily readable high level language
- Transferable coding language with other languages
- Uses OOP (Object oriented programing)
#### What are variables
- Placeholders to store data
- strings, booleans, integers
    - "This is a string" "" or ' '
    - Boolean is True or False (case-sensitive)
    - Integers is a number    
    
```python
first_name = "James"
last_name = "Barton"
age = 22
wage = 23.80
print(first_name)
print(last_name)
print(age)
print(first_name, last_name, age)
# how to find the variable
print(type(first_name))
print(type(last_name))
print(type(age))
print(type(wage))
```

### Operators

| Operand | Description | Example |
|:---------: |:----------------------------: |:--------: |
| + | add two operands (variables) together| X + y + 2 |
| - | subtract two operands (variables) | X - y - 2 |
| * | multiply two operands (variables) | X - y - 2 |
| / | divide two operands (variables) | X - y - 2 |
| % | Modulus - remainder of the division of left operand by the right | X - y - 2 |
| + | add two operands (variables) together| X + y + 2 |



## Comparison Operators



| Operand | Description | Example |
|:---------: |:----------------------------: |:--------: |
| > | True if left operand is greater than the right| x > y |
| < | True if left operand is less than the right| x < y |
| == | True if both operands are equal | x == y |
| != | True if both operands are equal | x != y |
| >= | True if left operand is greater than or equal to the right| x >= y |
| <= | True if left operand is less than or equal to the right| x <= y |

#### initial operators work
```python
value_1 = 6
value_2 = 7

print(value_2 > value_1)
name = "James"
age = 22
print(name.isalpha())  # isalpha checks if the value is alphabetical
print(name.isdigit())  # checks the value if it is a digit
print(name.startswith("J"))  # checks what the first letter begins with
```

```python
# value_1 = 6
# value_2 = 7
#
# print(value_2 > value_1)
# name = "James"
# age = 22
# print(name.isalpha())  # isalpha checks if the value is alphabetical
# print(name.isdigit())  # checks the value if it is a digit
# print(name.startswith("J"))  # checks what the first letter begins with

greetings = "Hello World!"
# H E L L O  _ W O R L D  !
# 0 1 2 3 4  5 6 7 8 9 10 11

print(greetings)  # prints the greetings variable
print(len(greetings))  # prints the length of the variable, how many characters(indexes) are there
print(greetings[:5])  # prints everything before the 5th index
print(greetings[6:])  # prints everything after the 6th index
print(greetings[:2])  # prints only the 'He'
print(greetings[3:5])  # prints the indexes between the 3rd and the 5th

white_spaces = "This has extra spaces         "
no_spaces = "This has extra spaces"
print(len(no_spaces))  # length of text with no extra spaces
print(len(white_spaces))  # length of text with extra spaces
print(len(white_spaces.strip()))  # length of text without the extra spaces

sentence = "here's SOME text with lot's of text"
print(sentence.count("text"))  # counts how many times text appears in the string
print(sentence.lower())  # change string case to lower case
print(sentence.upper())  # change string case to upper case
print(sentence.capitalize())  # capitalises the first letter in the string
print(sentence.replace("with", ","))  # replaces 'with' with a ','(only happens once, if there is more than one 'with', it would not be replaced )

first_name = "James"
last_name = "Barton"
int_age = 22
print(str(int_age))  # prints int_age as a string
print(type(str(int_age)))  # displays that the int is now a string
print(first_name, last_name, int_age)  # adding variable into a string using ','
print(first_name + " " + last_name + " " + str(int_age))  # adding spaces using '+'
print("Name: ", first_name, last_name, ".Age:", str(int_age))  # displays personal details, with the extra string details

# Find the method to cast string into an integer and display the value and the type after conversion
string_age = "22"
print(int(string_age))
print(type(int(string_age)))
print("{}, {}".format(int(string_age), type(int(string_age))))  # displays the string_age as a int, then displays the type value
print(f"{first_name} {last_name} is {int_age} Years Old")
```
