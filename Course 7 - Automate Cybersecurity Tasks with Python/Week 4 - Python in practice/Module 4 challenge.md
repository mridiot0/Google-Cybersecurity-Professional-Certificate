### Question 1
#### What are the three types of errors you will encounter while debugging?

* Syntax errors, exceptions, and comment errors
* [x] Syntax errors, logic errors, and exceptions
* Logic errors, comment errors, and iterative errors
* Exceptions, logic errors, iterative errors

### Question 2
#### The purpose of the following code is to search a list. Run this code, analyze its output, and then debug it.

```
def search_list(username):
    for item in username:
        print(item)
search_list(["elarson", "bmoreno", "tshah"])
```

#### What is the error related to?

* A misspelled variable
* A missing quotation mark (")
* A missing comma (,)
* [x] A missing colon (:)

### Question 3
#### The purpose of this code is to print "user flagged" if the username is "jhill", and otherwise to print "user okay". Run this code, analyze its output, and debug it.

```
def check_user(name):
    if name == "jhill":
        print("user flagged")
    else:
        print("user okay")
check_user("jhill")
```

#### How can you fix this error?

* [x] Add an else statement before the line that prints "user okay".
* Remove indentation from the line that prints "user okay" so that it is not part of the conditional.
* Use the != operator instead of the == operator in the conditional header.
* Call check_user() before the function definition.

### Question 4
#### You ask your code to divide something by 0, but an error occurs. What type of error is this?

* [x] Exception
* Index out of bounds
* Syntax error
* Logic error

### Question 5
#### When debugging code, what are effective ways to determine which sections of code are working properly? Select all that apply.

* Delete blank lines from the code
* [x] Use a debugger
* [x] Add print statements
* Add comments in the code

### Question 6
#### What does the following code do?

```
with open("logs.txt", "r") as file:
```

#### What does the code do?

* It copies a file called "logs.txt" into a new file "r".
* [x] It opens a file called "logs.txt" in read mode and stores it in a variable called file.
* It opens a file called "logs.txt" in write mode and stores it in a variable called file.
* It copies a file called "r" into a new file "logs.txt".

### Question 7
#### What does the following code do?

```
logins = "pwashing jhill tshah"
usernames = logins.split()
```

#### What does the code do?

* Splits a string variable called logins into single characters
* Removes the last username in the logins variable and stores the string in the usernames variable
* [x] Splits a string variable called logins into a list of strings and stores it in the variable usernames
* Removes the blank spaces that split the usernames in the variable logins and stores the string in the variable usernames

### Question 8
#### What is the process of converting data into a more readable format?

* Splitting
* Slicing
* [x] Parsing
* Debugging

### Question 9
#### What does the following code do?

```
read_text = text.read()
```

#### What does the code do?

* Splits the text variable, which contains a string, and stores it as a list in read_text
* Replaces the contents of the file read_text with the contents of the file text
* [x] Reads the text variable, which contains a file, and stores it as a string in read_text
* Reads the string text and stores it the file read_text

### Question 10
#### You want to check for unusual login activity. Specifically, you want to read a log file that contains information on each login attempt, including whether it failed or was successful. You should then parse the data into a logins list, and then you should separate all failed log entries into a separate failed_logins list. If you want to automate this through Python, what would be part of your code? Select three answers.

* A counter variable to keep track of the number of failed logins
* [x] A split() function to split the login information into a list
* [x] An if statement to check if a login attempt failed
* [x] A for loop to iterate through all items in the logins list