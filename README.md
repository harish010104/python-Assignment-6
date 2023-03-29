# python-Assignment-6
## Python Basic Assignment - 6
-------------------
### 1. What are escape characters, and how do you use them?
- In Python strings, the backslash(\) is a special character, also called the "escape" character. It is used in representing certain whitespace characters: "\t" is a tab, "\n" is a newline, and "\r" is a carriage return
- prefixing a special character with(\) turns it into an ordinary character. This is called "escaping". For example, " \\' " is the single quote character. 'It\'s Sunday' therefore is a valid string and equivalent to "It's Sunday".
---------------------
### 2. What do the escape characters n and t stand for?
- "\t" is for tab space, "\n" is for a newline
-----------------------
### 3. What is the way to include backslash characters in a string?
You need to append backslash with another backslash to include the backslash in your strings

eg
print("it's a back slash \ in a sentence")
print("it's a back slash \\ in a sentence")
print("it's a back slash \\\ in a sentence")
----------------
### 4. The string "Howl's Moving Castle" is a correct value. Why isn't the single quote character in the word Howl's not escaped a problem?
The string "Howl's Moving Castle" is a correct value. Why isn't the single quote character in the word Howl's not escaped a problem?
--------------
### 5. How do you write a string of newlines if you don't want to use the n character?
we can use Pythons multi line strings that done using triple quotes

Example:
string_multiline = """This is my
multi line
string by
name string_multiline"""
string_multiline
-------------
### 6. What are the values of the given expressions?

- 'Hello, world!'[1] 'e'
- 'Hello, world!'[0:5] 'Hello'
- 'Hello, world!'[:5] 'Hello'
- 'Hello, world!'[3:] 'lo, world!'
'Hello, world!'[1]
'Hello, world!'[0:5]
'Hello, world!'[:5]
'Hello, world!'[3:]
----------
### 7. What are the values of the following expressions?
- 'Hello'.upper() -> 'HELLO'
- 'Hello'.upper().isupper() -> True
- 'Hello'.upper().lower() -> 'hello'
'Hello'.upper() 
'Hello'.upper().isupper()
'Hello'.upper().lower()
-------------
### 8. What are the values of the following expressions?
- 'Remember, remember, the fifth of July.'.split() -> ['Remember,', 'remember,', 'the', 'fifth', 'of', 'July.']


- '-'.join('There can only one.'.split()) -> 'There-can-only-one.'
'Remember, remember, the fifth of July.'.split()
'-'.join('There can only one.'.split())
-----------------------
### 9. What are the methods for right-justifying, left-justifying, and centering a string?
# left justified
str1 ="Data Scienctist"
str1.ljust(19,";")
# right justified
str1 ="Data Scienctist"
str1.rjust(22,"-")
# center justified
str1 ="Center"
str1.center(40,'*')
---------------------
### 10. What is the best way to remove whitespace characters from the start or end?
We can use:
    
- lstrip() -> removes white spaces from left of the string
- rstrip() -> removes whitespaces from right of the string
str1 = "                    hello         "
print(str1)
print(str1.lstrip())
str1 = "hello                "
print(str1)
print(str1.rstrip())
