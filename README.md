

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

---

# Jan 22, 2022

*Today, I learned how to make first Django app.*

- To see the version of Django we type following command.

  > $ python -m django --version

- Creating a project

  We will need to auto-generate some code that establishes a Django project, a collection of settings for an instance of Django, including database configuration, Django-specific options and application-specific settings.

  > django-admin startproject mysite

This will create a mysite directory in our current directory.

startproject was created:

```
mysite/
    manage.py
    mysite/
        __init__.py
        settings.py
        urls.py
        asgi.py
        wsgi.py
```

- The development server

  We can change into the outer mysite directory as site.

> python manage.py runserver

- Creating the Polls app

  > python manage.py startapp polls

This will create a directory polls, which is laid out like this:

```
polls/
    __init__.py
    admin.py
    apps.py
    migrations/
        __init__.py
    models.py
    tests.py
    views.py
```

---

# Jan 23, 2022

*Today, I learned about SQL and MVC and how it works.*

---

# Jan 24, 2022

*Today, I learned about Models and the admin site in Django.*

---

# Jan 25, 2022

*Today, I learned about Views and templates in Django.*

---

# Jan 26, 2022

*Today, I learned about Forms and generic views in Django.*

---

# Jan 27, 2022

*Today, I learned about testing in Django.*

---

# Jan 28, 2022

*Today, I learned about Static files in Django.*

---

# Jan 31, 2022

*Today, I learned how to Customize the admin site in Django.*

---

# Feb 1,2022

*Today, I learned about basics of HTML and CSS.*

---

# Feb 2, 2022

*Today, I create the admin site for portfolio.*

* Using SSH Key in git hub:

  >git remote set-url origin git@github.com:sabina489/portfolio.git

* And push

>git push origin master

---

# Feb 3, 2022

*Today, I learned about basic html.*

---

# Feb 4, 2022

*Today, I learned about basics of css.*

---

# Feb 5, 2022

*Today, Hotel Website was created by using basics HTML and CSS.*

---

# Feb 7, 2022

*Today, templates and views was made for Portfolio.*

---

# Feb 8, 2022

*Gitignore for a Django project*

If we are using Git for version control, we need a Gitignore file to ignore all files that don’t matter and shouldn’t be in our git repository. Think of our virtual environment and all the .pyc files. Those are both generated and can be generated by anyone that has access to our code. Therefore, it’s unnecessary to add those to our repository.

There are a lot of different file types and specific folders that we don’t need. Even outside of Django. Think about our personal settings in VS Code (if ou use that). Here is a list which covers all things that you can ignore through gitignore for every Django project you start. Put this list in the root of your Django project and call it `.gitignore` (yes, with the dot!).

**We need to create .gitignore file outside the project.**

```
# Django #
*.log
*.pot
*.pyc
__pycache__
db.sqlite3
media

# Backup files # 
*.bak 

# If you are using PyCharm # 
# User-specific stuff
.idea/**/workspace.xml
.idea/**/tasks.xml
.idea/**/usage.statistics.xml
.idea/**/dictionaries
.idea/**/shelf

# AWS User-specific
.idea/**/aws.xml

# Generated files
.idea/**/contentModel.xml

# Sensitive or high-churn files
.idea/**/dataSources/
.idea/**/dataSources.ids
.idea/**/dataSources.local.xml
.idea/**/sqlDataSources.xml
.idea/**/dynamic.xml
.idea/**/uiDesigner.xml
.idea/**/dbnavigator.xml

# Gradle
.idea/**/gradle.xml
.idea/**/libraries

# File-based project format
*.iws

# IntelliJ
out/

# JIRA plugin
atlassian-ide-plugin.xml

# Python # 
*.py[cod] 
*$py.class 

# Distribution / packaging 
.Python build/ 
develop-eggs/ 
dist/ 
downloads/ 
eggs/ 
.eggs/ 
lib/ 
lib64/ 
parts/ 
sdist/ 
var/ 
wheels/ 
*.egg-info/ 
.installed.cfg 
*.egg 
*.manifest 
*.spec 

# Installer logs 
pip-log.txt 
pip-delete-this-directory.txt 

# Unit test / coverage reports 
htmlcov/ 
.tox/ 
.coverage 
.coverage.* 
.cache 
.pytest_cache/ 
nosetests.xml 
coverage.xml 
*.cover 
.hypothesis/ 

# Jupyter Notebook 
.ipynb_checkpoints 

# pyenv 
.python-version 

# celery 
celerybeat-schedule.* 

# SageMath parsed files 
*.sage.py 

# Environments 
.env 
.venv 
env/ 
venv/ 
ENV/ 
env.bak/ 
venv.bak/ 

# mkdocs documentation 
/site 

# mypy 
.mypy_cache/ 

# Sublime Text # 
*.tmlanguage.cache 
*.tmPreferences.cache 
*.stTheme.cache 
*.sublime-workspace 
*.sublime-project 

# sftp configuration file 
sftp-config.json 

# Package control specific files Package 
Control.last-run 
Control.ca-list 
Control.ca-bundle 
Control.system-ca-bundle 
GitHub.sublime-settings 

# Visual Studio Code # 
.vscode/* 
!.vscode/settings.json 
!.vscode/tasks.json 
!.vscode/launch.json 
!.vscode/extensions.json 
.history
```

**We need to commit by following commands: **

```
git rm -r --cached . && git add . && git commit -am "Remove ignored files"
```

---

 # March 21, 2022

## DJANGO REST FRAMEWORK

*Django REST framework is a powerful and flexible toolkit for building Web APIs.*



**Project setup**

*Create the project directory*

> mkdir tutorial
>
> cd tutorial

*Create a virtual environment to isolate our package dependencies locally*

> python3 -m venv env
>
> source env/bin/activate

*Install Django and Django Rest fromework into the virtual environment*

> pip install django
>
> pin install djangorestframework
>
> cd tutorail
>
> django-admin startapp quickstart
>
> cd ..

*The project layout should look like.*

>```
>$ pwd
><some path>/tutorial
>$ find .
>.
>./manage.py
>./tutorial
>./tutorial/__init__.py
>./tutorial/quickstart
>./tutorial/quickstart/__init__.py
>./tutorial/quickstart/admin.py
>./tutorial/quickstart/apps.py
>./tutorial/quickstart/migrations
>./tutorial/quickstart/migrations/__init__.py
>./tutorial/quickstart/models.py
>./tutorial/quickstart/tests.py
>./tutorial/quickstart/views.py
>./tutorial/asgi.py
>./tutorial/settings.py
>./tutorial/urls.py
>./tutorial/wsgi.py
>```

*Now sync our database for the first time:*

> python manage.py migrate

*We'll also create an initial user named admin with a password of password123.*

>python manage.py createsuperuser --email admin@example.com --username admin

**Serializers**

*First we are going to define serializers. create a new module named tutorail/quickstart/serializers.pu*

>```
>from django.contrib.auth.models import User, Group
>from rest_framework import serializers
>
>
>class UserSerializer(serializers.HyperlinkedModelSerializer):
>    class Meta:
>        model = User
>        fields = ['url', 'username', 'email', 'groups']
>
>
>class GroupSerializer(serializers.HyperlinkedModelSerializer):
>    class Meta:
>        model = Group
>        fields = ['url', 'name']
>```

**Views**

*Open tutorail/quickstart/views.py*

>```
>from django.contrib.auth.models import User, Group
>from rest_framework import viewsets
>from rest_framework import permissions
>from tutorial.quickstart.serializers import UserSerializer, GroupSerializer
>
>
>class UserViewSet(viewsets.ModelViewSet):
>    """
>    API endpoint that allows users to be viewed or edited.
>    """
>    queryset = User.objects.all().order_by('-date_joined')
>    serializer_class = UserSerializer
>    permission_classes = [permissions.IsAuthenticated]
>
>
>class GroupViewSet(viewsets.ModelViewSet):
>    """
>    API endpoint that allows groups to be viewed or edited.
>    """
>    queryset = Group.objects.all()
>    serializer_class = GroupSerializer
>    permission_classes = [permissions.IsAuthenticated]
>```

*Rather than wirte multiple views we are grouping together all the common behaviour into classes called ViewSets.*

**URLs**

*Now let's wire up the API URLs. on the tutorail/urls.py*

>```
>from django.urls import include, path
>from rest_framework import routers
>from tutorial.quickstart import views
>
>router = routers.DefaultRouter()
>router.register(r'users', views.UserViewSet)
>router.register(r'groups', views.GroupViewSet)
>
># Wire up our API using automatic URL routing.
># Additionally, we include login URLs for the browsable API.
>urlpatterns = [
>    path('', include(router.urls)),
>    path('api-auth/', include('rest_framework.urls', namespace='rest_framework'))
>]
>```

**Pagination**

*Pagination allows us to control how many objects per page are returned.*

*To enable it add the following lines to tutorial/settings.py.*

>```
>REST_FRAMEWORK = {
>    'DEFAULT_PAGINATION_CLASS': 'rest_framework.pagination.PageNumberPagination',
>    'PAGE_SIZE': 10
>}
>```

**Settings**

*add 'rest_framework' to INSTALLED_APPS. The settings module module will be in tutorail/settings.py.*

```
INSTALLED_APPS = [
    ...
    'rest_framework',
]
```

**Testing our API**

> python manage.py runserver

*Directly through the browser, going to the URL http://127.0.0.1:8000/users/*

---

**1.Serialization**

*Once we creat a new project to work we create an app that we will use to create a imple Web API.*

>python manage.py startapp snippets

Edit the tutorail/settings.py file

>```
>INSTALLED_APPS = [
>    ...
>    'rest_framework',
>    'snippets',
>]
>```

Create a model to work with

Creating a simple Snippet model that is used to store code snippets. 

*snippets/models.py*

```
from django.db import models
from pygments.lexers import get_all_lexers
from pygments.styles import get_all_styles

LEXERS = [item for item in get_all_lexers() if item[1]]
LANGUAGE_CHOICES = sorted([(item[1][0], item[0]) for item in LEXERS])
STYLE_CHOICES = sorted([(item, item) for item in get_all_styles()])


class Snippet(models.Model):
    created = models.DateTimeField(auto_now_add=True)
    title = models.CharField(max_length=100, blank=True, default='')
    code = models.TextField()
    linenos = models.BooleanField(default=False)
    language = models.CharField(choices=LANGUAGE_CHOICES, default='python', max_length=100)
    style = models.CharField(choices=STYLE_CHOICES, default='friendly', max_length=100)

    class Meta:
        ordering = ['created']
```

**We will also need to create an initial migration for our snippet model, and sync the database for the first time**

>python manage.py makemigrations snippets
>
>python manage.py migrate snippets

**Creating a Serializer class**

*A serializer class is very similar to a Django Form class, and includes similar validation flags on the various fields such as required, max_length and default.*

*Create a file in the snippets directory named serializers.py and add the following:*

>```
>from rest_framework import serializers
>from snippets.models import Snippet, LANGUAGE_CHOICES, STYLE_CHOICES
>
>
>class SnippetSerializer(serializers.Serializer):
>    id = serializers.IntegerField(read_only=True)
>    title = serializers.CharField(required=False, allow_blank=True, max_length=100)
>    code = serializers.CharField(style={'base_template': 'textarea.html'})
>    linenos = serializers.BooleanField(required=False)
>    language = serializers.ChoiceField(choices=LANGUAGE_CHOICES, default='python')
>    style = serializers.ChoiceField(choices=STYLE_CHOICES, default='friendly')
>
>    def create(self, validated_data):
>        """
>        Create and return a new `Snippet` instance, given the validated data.
>        """
>        return Snippet.objects.create(**validated_data)
>
>    def update(self, instance, validated_data):
>        """
>        Update and return an existing `Snippet` instance, given the validated data.
>        """
>        instance.title = validated_data.get('title', instance.title)
>        instance.code = validated_data.get('code', instance.code)
>        instance.linenos = validated_data.get('linenos', instance.linenos)
>        instance.language = validated_data.get('language', instance.language)
>        instance.style = validated_data.get('style', instance.style)
>        instance.save()
>        return instance
>```

**Writing regular Django views using our Serializer**

Edi the snippets/views.py file, and add the following:

>```
>from django.http import HttpResponse, JsonResponse
>from django.views.decorators.csrf import csrf_exempt
>from rest_framework.parsers import JSONParser
>from snippets.models import Snippet
>from snippets.serializers import SnippetSerializer
>
>@csrf_exempt
>def snippet_list(request):
>    """
>    List all code snippets, or create a new snippet.
>    """
>    if request.method == 'GET':
>        snippets = Snippet.objects.all()
>        serializer = SnippetSerializer(snippets, many=True)
>        return JsonResponse(serializer.data, safe=False)
>
>    elif request.method == 'POST':
>        data = JSONParser().parse(request)
>        serializer = SnippetSerializer(data=data)
>        if serializer.is_valid():
>            serializer.save()
>            return JsonResponse(serializer.data, status=201)
>        return JsonResponse(serializer.errors, status=400)
>@csrf_exempt
>def snippet_detail(request, pk):
>    """
>    Retrieve, update or delete a code snippet.
>    """
>    try:
>        snippet = Snippet.objects.get(pk=pk)
>    except Snippet.DoesNotExist:
>        return HttpResponse(status=404)
>
>    if request.method == 'GET':
>        serializer = SnippetSerializer(snippet)
>        return JsonResponse(serializer.data)
>
>    elif request.method == 'PUT':
>        data = JSONParser().parse(request)
>        serializer = SnippetSerializer(snippet, data=data)
>        if serializer.is_valid():
>            serializer.save()
>            return JsonResponse(serializer.data)
>        return JsonResponse(serializer.errors, status=400)
>
>    elif request.method == 'DELETE':
>        snippet.delete()
>        return HttpResponse(status=204)
> 
>```

**Finally, we need to wire these views up. Create the snippets/urls.py file:**

> >```
> >from django.urls import path
> >from snippets import views
> >
> >urlpatterns = [
> >    path('snippets/', views.snippet_list),
> >    path('snippets/<int:pk>/', views.snippet_detail),
> >]
> >```

**We also need to wire up the root urlconf, in the tutorial/urls.py file, to include our snippet app's URLs.**

>```
>from django.urls import path, include
>
>urlpatterns = [
>    path('', include('snippets.urls')),
>]
>```

**Testing our first attempt at a Web API**

>python manage.py runserver

---



