# Strings
* Type of challenge: **learning**
* Duration: **60 min**
* Team challenge: **solo**

# Learning objectives
At the end of this challenge you should:
* understand the concept of strings
* be able to concatenate strings
* be able to operate on strings

# The mission
This challenge will have you play around with the concept of **strings**, complete the exercises down below after you’ve read the explanations.

Strings seems to be a very limited data type until you realise that they are almost like arrays. Indeed, they are composed of character at different index of the string, meaning you can actually play around with them.

Hopefully, most if not all high level languages have plenty of predefined functions to work with strings or character, that means a simpler life for you.

Example
```
string text = "hello"
output(hello[1]) // output e

// check if the parameter is a letter
is_letter('a') // returns true
is_letter('4') // returns false

// check if the parameter is a number
is_number('a') // returns false
is_number('4') // returns true

// check if the parameter is a lowercase
is_lowercase('a') // returns true
is_lowercase('A') // returns false

// check if the parameter is uppercase
is_uppercase('A') // returns true
is_uppercase('a') // returns false

// returns a lowercase character
lowercase('A') // returns a

// returns an uppercase character
uppercase('a') // returns A

// returns a sub part of a string
sub_string('hello world',6,5) // returns world

// returns the position of a given sub string in a string
position('hello world','w') // returns 6
```

## Exercises

*I will be using [Python3](https://repl.it/languages/python3) to write and test the algorithms*

Instructions
* write your algorithm on paper
* detail each and every step
* indicates the types of used variables

I - concatenation
- [x] Write a function which receives two strings and returns them as one string.

```
def addStr():
    string1=str(input("Please enter first string:"))
    string2=str(input("Please enter second string:"))
    return(string1+string2)

string=addStr()
print(string)
```

II - lowercase
- [ ] Write a function which receives a character in uppercase and prints it in lowercase.

```
def lowerStr():
    string=str(input("Please enter a string in uppercase:"))
    print(string.lower())
    
lowerStr()
```

III - uppercase
- [x] Write a function which receives a string in lowercase and returns an uppercase sentence.

```
def upperStr():
    string=str(input("Please enter a string in lowercase:"))
    print(string.upper())

upperStr()
```

IV - convert name
- [ ] Write a function which receives a name in this format "Doe, John" an returns it in this format "John Doe"

```
def inputName():
    string=str(input("Please enter your name in this format => Last name, Name:"))
    separator=string.index(",")
    print(string[separator+1:],string[0:separator])

inputName()
```

V - whitespace
- [ ] Write a function which receives a sentence full of whitespace and returns it without them.

## Resources
* [conventions](https://github.com/becodeorg/BXL-Swartz-4-27/blob/master/1.The-Field/7.Algorithmic/conventions.adoc)
