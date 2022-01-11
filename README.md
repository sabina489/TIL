

# TIL (Today I Learned)



## Nov 15, 2021

### Today, I learned about Linux commands.

**Basic Commands**

**Commands**                                                                 **Description**

*ls*                                                                                      List directory contents.

*ls -a*                                                                                  *List all directories.*

*ls -l*                                                                                  It shows some extra informations (time,date).

*cd*                                                                                    Change to directory.

*cd ..*                                                                                  *Back to the home.*

*cd ~*                                                                                   *Back to the home.*

*mv*                                                                                    Rename or move files.

*mkdir*                                                                              *Create a new directory.*

*pwd*                                                                                 *Display the pathname for the current directory.*

*touch filename*                                                              *Create an empty file with the specified name.*

*clear*                                                                               *To clear the screen*

*cat [filename]*                                                                *Display file's contents to the standard output device.



----

----



## Nov 16, 2021

### Today, I learned about git.

### Basic Commands

- *git init*                                                               //Initialize Local Git Repository
- git add  **<file>**                                             *//Add Files to Index*
- *git status*                                                          *//Check Status of Working Tree*
- *git commit*  *-m "Initial commit"*                      *//Commit Changes in Index*
- *git remote*  *-v*                                                     *//Adding a remote*
- *git clone*                                                        *//Is used to copy an existing Git repository from a server to the local machine.*
- *git push*                                                     *//Push to Remote Repository*

*I learned how to connect to git-hub with ssh key.*

> Hence, different git operations were learned and got familiar on writing TIL.

---

---

## Nov 17, 2021

### Today, I learned about Branching in GIt.

- *To create a new branch* :- *git branch <name>*

- *To switch to an existing brance* :- *git checkout <name>*

- *To create a new branch and switch to it* :- *git checkout -b <name>*

  ---

  

### Listing branches 

​                        **Goal**                                                            **Command**            

*List local branches*                                                       *git branch*

*List local branches verbose*                                        *git branch -v*

*List remote and local branches*                                 git branch -a 

*list remote and local branches(verbose)*                   *git branch -av*

*list remote branches*                                                  *git branch -r*

*list remote branches with latest commit*                 *git branch -rv*

*List merged branches*                                                *git branch --merged*

*List unmerged branches*                                            *git branch --no merged*

*List branches containing commit*                             *git branch --contains [<commit>]*

---

### Delete a remote branch

*To delete a remote branch* :- *git push origin --delete <branchName>*

---



## Nov 18, 2021

### Today, I learned about pull request in Git-Hub.

*Pull requests let us tell others about changes we have pushed to a branch in a repository on Git-Hub* .

---

## Nov 19, 2021

### *Today, I learned about variables, numbers, strings in Python.*

**1. Variables**

*To create a variable in Python, all we need to do is specify the variable name, and then assign a value to it.*

```
<variable name> = <value>
```

* A variable name must start with a letter or the underscore character.

* A variable name cannot start with a number.

* A variable name only contain alpha-numeric characters and underscores.

* Variable names are case-sensitive.

  ---

  

## Nov 21, 2021

### Today, I learned about methods, lists, tuples, modules,prompting and passing, reading and writing the files in python.

---

## Nov 22, 2021

### Today, I learned about functions and variables, how function can return something.

* *Functions : A function is a block of code which only runs when it is called .*

  1. Default values for arguments

  ```
  def function_name(var="value"):
  ```

  2. Using Multiple arguments

     ```
     def function_name(*args):
     ```

  3. Unpacking arguments

     ```
     def function_name(int, string, string):
     list=[1, "name1", "name2"]
     function_name=(*list)
     ```

  4. Sets(a={}), dictionaries(a={'key':'value'})

     ```
     to show dictionary content
     for k, v in dic.items()
     print(k+", "+v)
     ```

  ---

  ---

  

### I learned about Strings, Bytes, and Character Encodings . 

*The text file simply contains a list of human language names that are encoded in UTF-8.*

---

## Nov 23, 2021

### Today, I learned about IF-STATEMENT, ELSE-IF STATEMENT, Loops and Lists, While Loops in Python.

---

## Nov 24, 2021

### Today, I learned about List and Dictionary in Python.

---

# Nov 25, 2021

*Today, I learned about Modules, Classes and Objects in Python.*

---

# Nov 26, 2021

*Today, I learned about Inheritance in Python.*

* *Python Inheritance* : Inheritance allows us to define a class that inherits all the methods and properties from another class.

* Parent class is the class being inherited from, also called base class.

* Child class is the class that inherits from another class, also called derived class.

  *We use a Is-A when we talk about objects and classes being related to each other by a class relationship.*

  *We use a Has-A when we talk about objects and classes that are related only because they reference each other.*

  ---

  # Nov 28, 2021

  *Today, I learned how to make a game in Python.*

  ---

  ---

  # Dec 2, 2021

  *Today, I learned about computation, uses of computation, how to solve a problem.*

  - Computer science is the study of computation and information.
  - It investigates the computational algorithms that can be applied to acquire, represent, generate, transform, and communicate knowledge that solves computational problems.
  - There are many types of informations. A number, string, text, image, video are the kinds of information.
  - An algorithm is the sequence of steps used to perform a computation.
  - Communication, information storage and retrieval, device monitoring and control, information encryption and decryption, and simulation are the uses of computation.
  - There are two kinds of translators : compilers and interpreters. 
  - An interpreter translates one statement of a program into machine language by interpreting that line.

  **Problem-based learning**

  - First we need to introduce a problem.
  - Then, identify the knowledge/skills required.
  - After that we need to learn knowledge or skill as it is needed.

  *Advantages of problem-based learning*

  1. The learner may be more motivated to learn the techniques and tools.
  2. The learner learns problem solving in addition to the techniques and tools.
  3. There may be higher transfer of learning to other problem domains.

  *Disadvantage of problem-based learning*

  1. Some learners may be uncomfortable trying to solve a problem before they know the necessary knowledge.
  2. It may take extra time to learn.

  ---

  # Dec 3, 2021

  *Today, I learned how we can use computational problem solving techniques to create games, how to install virtual machine and played hacking game.*

  ---

  # Dec 5, 2021

  *Today, I leaned about creating version*, observed and played  the first version of Hacking. Described and test plan was created for Hacking Version 1.

  **Feature selection**

  Feature selection determines the feature set that each version must implement. One of the criteria for future selection is balanced feature sets.

  Second criteria for feature selection is Feature Dependency.

  **Game Version**

  - We break a big problem into several smaller problems called versions that are easier to solve.
  - It is useful to split a single feature into multiple features to help balance the feature sets. For example, using a Window involves both opening a Window and closing a Window.
  
  **First version of Hacking**

  - A message is printed below my guess, it indicates that my guess is incorrect even though I entered the correct answer.
  - Press enter to end the game.
  
  **Description of Hacking Version 1**

  - A description of a game is an explanation of what happens as the game is played.
  - The description includes aspects, such as what the game looks like, how it changes, and how it responds to player actions.
  - A description describes the features that must be included in the game, and how these features interact.
  
  **Test plan**

  - A test plan is a group of tests that are performed on a program to make sure that it performs as expected. 
  - Here, test plans only contain functional tests. Each functional test consists of and action and a group of questions.
  - A tester manually performs the action and uses the group of questions to evaluate whether the game responds to that action as described in the game description.
  - Each test is phrases as a yes or no question. All the answers must be yes for the program to be completely correct.
  
  ---

  # Dec 6,2021

  *I learned about algorithm.*

  - An algorithm is a sequence of steps that solves a problem.
  - An algorithm is more precise than a test plan because its steps define the logic of the solution. 
  - Although an algorithm is more precise than a test plan, it is less precise than code.
  
  ---

  # Dec 7,2021

  *Today, I learned how to start the Wing IDE and configure it for the Python Shell.*

  *Learned about Python expressions and Python Interpretation*

  **Python Expressions**

  1. Literal Strings: It can be enclosed in single or double quotes. example. 'hello', 'Python',etc.
  2. Function call: Function is like a machine that has inputs and outputs. Example: len('hello') here, len function is a built-in function, where len is short for length. The literal string was used as the function argument.
  
  **Token in Python**

  - A token is constructed from one or more characters where each character can be a letter, a digit, a symbol, a special character, or whitespace. Whitespace is a space, a tab, or a page break character also called a form feed.
  - Python has five different kinds of tokens.
  
  1. **Delimiter** : In programming languages, delimiters are analogous to punctuation in natural language. For example, left paren and right paren are delimiter tokens in Python.
  2. **Literal** : Literals in programming languages are analogous to different parts of speech such as noun, verb and pronoun.
  3. **Identifier **: Identifiers in programming languages are analogous to a pronoun.
  4. **Operator**
  5. **Keyword**

  ---

  # Dec 8, 2021

  *Learned about Lexical Rules, Tables and Sample Problem (identifier, literal and delimiter.*

  **Current Lexical Rules:**

  **identifier**
  
  - start with a letter or underscore, and is followed by zero or more letters, underscores or digits.
  
  **literal string**
  
  - starts with a quote, followed by zero or more non-quote characters and ends with a quote.
  
  **literal integer**
  
  - one ore more digits.
  
  **literal float**
  
  - one dot, one or more digits and no other characters.
  
  **longest token rule**
  
  - when creating a token, create the longest token possible.
  
  **whitespace rule**
  
  for whitespace not at the start of a line:
  
  - if whitespace is inside a literal string it is part of the literal string.
  - otherwise, its ends the current token and no token is created for it.
  
  
  
  **Current Lexical tables:**
  
  **delimiter**
  
  | (    | )    | [    | ]    | {    |
  | ---- | ---- | ---- | ---- | :--- |
  | }    | ,    | :    | .    | ;    |
  | @    | =    | ->   | +=   | -=   |
  | *=   | /=   | //=  | %=   | &=   |
  | \|=  | ^=   | >>=  | <<=  | **=  |

 **For example**

```
len('hello')
```

- 1st taken and token kind is **len identifier**
- 2nd token and token kind is **( delimiter**
- 3rd token and token kind is **'hello' literal string**
- 4th token and token kind is **) delimiter**

**Python interpretation process**

1. lexical analysis: combine characters into tokens.
2. syntax analysis: combine tokens into statements.
3. semantic analysis: evaluate the statement.

**Python Objects**

- The Python interpreter creates objects to represent data in computer memory.
- Each object has an identity, a type, and a value.
- An object's identity is determined when the object is created.
- Once the object is created, it is unique and immutable, which means it cannot be changed.
- An object's type determines its format or shape in memory and how it is interpreted during computations.

**Python Semantics of Literals, Identifiers and Function Calls**

- Semantic Rule for Literal: create a new object for the literal.
- Semantic Rule for Identifier: if the identifier is in the namespace, dereference it to get the result object, otherwise report an error.
- Semantic Rule for function call: evaluate the identifier to obtain a function object. If there is an expression, evaluate it to obtain an argument object. If there is an argument object, pass it into the function. evaluate the function code to obtain a result object.

---

# Dec 9,2021

*I learned about Python Program Interpretation*

**-** The python interpreter uses lexical analysis to create tokens for the entire program. It then checks the syntax of each statement in order from the first statement to the last statement. Finally, it uses semantic analysis to evaluate each statement in order.

**print function**

- print function displays a human-readable form of its argument object to selectively display two of the three objects in the program.
- The print function returns a unique object whose type is NoneType.

---

# Dec 12, 2021

*Today, I observed and played Hacking Version 2 game and used the description builder to create a description for hacking version 2.*

---

# Dec 15, 2021

*Functional test plan was created for Hacking Version 2 and learned about Python Assignment Statement.*

**Python Assignment Statement**

- An assignment statement is used to evaluate an expression and bind an identifier to the result object.

---

# Dec 16, 2021

*Algorithm was created for Hacking Version 2 and learned about Python Binary Expression and Operator Token*.

**Semantic Rules for binary expression**

- assignment statement -as

1. plus evaluate the expression to obtain a result object.
2. if the identifier is not in the namespace, add it to the namespace.
3. bind the identifier to this result object.

- new binary expression -be

1. +evaluate  the left expression to get the first operand object.
2. +evaluate the right expression to get the second operand object.
3. identify the operator function based on the binary operator and the *type* of the two operands.
4. apply the binary operator's function.

- function call -fc

1. +evaluate the identifier to obtain a function object.
2. ^ if there is an expression, evaluate it to obtain an argument object.
3. if there is an argument object, pass it to the function.
4. evaluate the function code to obtain a result object.

- identifier -id
  - if the identifier is in the namespace, dereference it to get the result object, otherwise report an error.
- literal -li

create a new object for the literal.

---

# Dec 17,2021

*Python Import statement and Keyword Token and Python Multi-argument Function Call was learned*

- An import statement allows us to use functions, types and other objects from a library module.
- A module is a Python program with it's own statements and namespace.
- An import statement imports identifiers from a module into our programs namespace so that we can use the objects the identifiers are bound to.

**Multi-argument Function Call**

- Different functions support different numbers of arguments.
- Many Python functions can accept a variable number of arguments. For example, when the print function is called with no argument, it displays a blank line. When the print function is called with more than one argument, it evaluates its argument expressions and displays all the results objects on one line separated by single blanks.

---

# Dec 19, 2021

*Today, I learned Python Method Call and Attribute Reference and program for Hacking Version 2 was implemented.*

---

# Dec 20,2021

*Today, I observed, played and Described Hacking Version 3.* *Test Plan Algorithm was created for Hacking Version 3.*

*Learned about if Statement and Boolean Type.*

- if statement is a statement that has another statement inside of it.
- A statement that includes another statement is called a compound statement.
- A statement that does not include another statement, is called a simple statement.
- The if statement is a compound statement and the expression, assignment and import statements are simple statements.

---

# Dec 21, 2021

*Today, I learned elif and else clauses, Keyword Operator, Short Circuit Evaluation, Unary Expression, and Operator Precedence in Python.*

---

# Dec 22, 2021

*Today, I learned Python Sequences and Subscription, Python Tuple and List Types.*

- A sequence is a finite ordered group of elements where each object has a numerical index between o and 1 less than the number of elements in the sequence.
- There is no sequence type in Python. Instead, sequences are category that include several different Python types.
- Python subscription is analogous to using subscripts in mathematics. For example, I can reference the string element of hello at index one, using this expression which is pronounced hello of one.
- A tuple is a sequence whose elements can be any type.
- A list is like a tuple, in that, its elements can be any type.

---

# Dec 23, 2021

*Today, I learned Python Sequences Element Replacement and Python for statement. Also Program for Hacking-Version 4 is learned.*

- A for statement,often called a for loop, is used to repeat other statements a definite number of times.
- There are many situations in which we would like to apply the same computation to each element individually. So, we can use a for statement to evaluate a group of statements as many times as necessary without rewriting those statements.
- A for statement is another kind of compound statement.

---

# Dec 24, 2021

*Today, Hacking Version 5 is observed, played and described. Test Plan and Algorithm was created for Hacking Version 5. Also Python while statement was learned.*

- A while statement is a new repetition control structure that uses a Boolean expression to control the repetition instead of using a sequence.
- A while statement is a compound statement.
- The header of a while statement consists of the while keyword token, an expression, and a colon delimiter. The header is followed by the suite non-terminal state.
- A while statement is called an indefinite repetition control structure since we don't know ahead of time how many times it's suite will be evaluated.

---

# Dec 26, 2021

*Today, I learned about Python functions.*

- Functions allow us to create blocks of code that can be easily executed many times, without needing to constantly rewrite the entire block of code.
- Creating clean repeatable code is a key part of becoming an effective programmer.
-  A complete python program consists of blocks and there are three kinds of Python blocks: modules, functions and classes.

---

# Dec 27, 2021

*Today, I learned Python Return Statement, Python Side Effects and learned and observed program for Hacking Version 6.*

- The return statement consists of the keyword token return, followed by an optional expression.
- Unlike other simple statements, a return statement can only be used in a function definition suite.

---

# Dec 28,2021

*Today, I learned about side effects in Python and solved the quiz questions.*

---

# Dec 29, 2021

*Today, program for Hacking Version 6 was learned.*

---

# Dec 30, 2021

*Today, observed, played, described and test plan was created for Hacking Version 7.*

---

# Dec 31, 2021

*Today, Algorithm was created and Program was implemented for Hacking Version 7.*

---

# Jan 2, 2022

*Today, Poke the Dots was introduced. Also observed, played, described and test plan was created for Poke the Dots Version 1.*

---

# Jan 3, 2022

*Today, I learned about import statement variations and pass statement in Python. Also Algorithm was created and program was implemented for Poke the Dots Version 1.*

---

# Jan 4, 2022

*Today, I learned about Class Definition in Python.*

---

# Jan 11, 2022

*Today, I learned how to create a new environment*

* Create a new environment

> > conda create --name django python=3

* To use, or "activate" the new environment, type the following:

> >conda activate django

* To deactivate Anaconda environment:

> > conda deactivate

* To see a list of all environments, type:

> conda info --envs

* Change the current environment back to the default(base):

> > source activate





























