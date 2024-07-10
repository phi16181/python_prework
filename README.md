<b>Pre-work</b>

In order for you to be successful in ML, you need to understand how to utilize the Python programming language for data science and data analytics. You might also be using tools like R as well, but you’ll be starting your journey with Python so I’ve provided some resources to help you get started early. 

Before moving on, it is a great idea to come up to speed on some foundational concepts of data analytics so you can better understand 'how' you'll be using Python to solve problems within this space.  

It is very important for you to understand that we do not use the Python programming language in the same manner that a software engineer would.  In other words,  you are not learning to be programmers, per se, but rather how to use Python to solve real-world data analytics and data science problems. We most certainly will be writing code,  but not in the same manor as someone that would be developing a full piece of software would.

<center><img src="images/jup.png" width="400" height="200" align="center"/></center>

One of the main tools you will be using during the pre-work is called a Jupyter notebook.  As a matter of fact,  you are reading this very work in a Jupyter notebook! Click on <a href="https://www.youtube.com/watch?v=q_BzsPxwLOE&feature=emb_logo" target="new">this link</a> to learn more about this important tool!

<center><img src="images/jupy1.png" width="600" height="400" align="center"/></center>

<b>Environment Setup</b>

Obviously, you will also be using Python extensively, but chances are you don't have python installed on your own machine so a good alternative is using a remote environment called Google Collaboratory to provide access to Python. Eventually, you’ll be setting up your own working environment so dont worry too much about doing so locally just yet. I've included an introduction to Google Collaboratory video for you below. Feel free to watch it and learn about Google Colab, but you do not need to view all the way to the end to hear about Tensorflow as that is a little beyond what youre ready to do just yet!

<a href="https://www.youtube.com/watch?v=inN8seMm7UI" target="new">Click here for video</a>

<center><img src="images/colab4.png" align="center"/></center>

<b>Lets get started</b>

To get started with Colab, just open a browser（I recommend Google Chrome or Firefox), and input the following URL: https://colab.research.google.com/ You will see the following webpage:

<center><img src="images/colab1.png"></center>

Just choose to create a new Python 3 notebook. Then you can see a fully configured Python running environment.

<center><img src="images/colab2.png"></center>

Although you did not go through any installation processes, it still contains almost all the modules you need for data science analysis. These tools include but are not limited to Numpy, Scipy, Pandas, etc. Even deep learning frameworks, such as Tensorflow, Keras and Pytorch are also included.

<b>Help!</b>

As a beginning Python user, it is very common for students to ask for help so knowing where to do so and how to do so is vital to your success.  In this pre-work, I have provided many different opportunities and ways for you to accomplish this, but remember, knowing how to solve problems on your own is key to being an excellent data scientist!

Let's take a look at how you can use a very common references that can be supplements for help:

First things first: Start assembling a good list of references; these will help you when you are truly stuck and need a quick definition or directions on 'how to use' something. Here are some good starting points for Python:

1. <a href="http://greenteapress.com/thinkpython2/thinkpython2.pdf">Think Python</a>
2. <a href="http://www.oreilly.com/programming/free/files/a-whirlwind-tour-of-python.pdf">A Whirlwind Tour of Python</a>
3. <a href="https://docs.python.org/3/reference/">The Python Language Reference</a>
4. <a href="https://jakevdp.github.io/PythonDataScienceHandbook/">Data Science Handbook</a>
5. <a href="https://www.amazon.com/Statistics-Absolute-Beginners-English-Introduction-ebook/dp/B0761PT1FD/ref=tmm_kin_title_sr?_encoding=UTF8&qid=1537990372&sr=8-1-spons">Statistics for Absolute Beginners: A Plain English Introduction</a>
6. <a href="https://www.amazon.com/Statistics-Utterly-Confused-Lloyd-Jaisingh/dp/0071461930/ref=sr_1_1?ie=UTF8&qid=1538660249&sr=8-1&keywords=statistics+for+the+utterly+confused">Statistics for the Utterly Confused</a>
7. <a href="https://docs.rapidminer.com/downloads/DataMiningForTheMasses.pdf">Section One: Data Mining for the Masses</a> Note: Do not worry about the mention of RapidMiner and/or OpenOffice, but rather just focus on the content.

Another excellent of getting help is to ask for it online! You do this easily and clearly by sharing your notebook with others using the 'share' button at the top of the screen.

<center><img src="images/colab3.png"></center>

Then, choose “copy link”, and the link will be saved in your clipboard. Put the link and the problem description together, and post them on Python’s official forum or a discussion board like 
<a href="https://stackoverflow.com">StackOverFlow</a>. 

<i>Note: Be careful visiting discussion boards in general as many of the more experienced members of the community might not be very willing to help folks that are just starting out. Just letting you know in advance! Be sure to spend time trying to solve the problem yourself before posting to a forum, and tell people the things you tried that didn’t work.</i>

People just need to click the link and they will be able to see all your codes and error information, and even better, they can run the copy of your notebook easily.

In fact, Google Colab provides you a very useful function to find possible answers. Whenever you encounter an error message, you can see a “Search Stack Overflow” button.

For more information on using Google Colab for learning Python, please visit the following: <a href="https://towardsdatascience.com/how-to-practice-python-with-google-colab-45fc6b7d118b">How to Practice Python Programming with Google Colab?</a>

<b><h1>Ok, lets dive into the basics of Python!</h1></b>

Now it's time for you to dive into learning the very basics of Python!

Before you get started coding you need to be aware of 'how' to properly code in Python. Believe it or not, how you code says a lot about your level of proficiency about Python and even your devotion to it in general. Have a quick read of the following article so you can understand what 'Pythonic' coding and PEP8 are: https://hub.packtpub.com/write-python-code-or-pythonic-code/

<b>To begin this task start Jupyter Notebook in Google Collab and create a new Notebook and save it on Google Collab. You will be using this notebook throughout the rest of the pre-work so be sure it is easy to find!</b>

<h1>Libraries or Modules</h1>

Just like in may similar languages, most of the functionality in Python is provided by modules; these are also sometimes referred to as libraries. Python already contains a large number of modules that assist us with many tasks like working with files, working with Math and even common tasks for servers and networking.  The best part about using libraries or modules is we can easily import them into our notebooks or projects and utilize everything that has already been created within each module. We can easily accomplish this by using the import statement in Python as follows:


```python
import name of module
```

where 'name of module' is the name of the module we want to import. Remember if the module isn't already included within Python, you'll need to install it into your local environment (we'll do this later on your local machine).

Here is an example that imports the math module:


```python
import math
```

and since math already includes numerous functions we can now access those pre-made functions anytime we need them. For example:


```python
math.sqrt(25)
```

returns a value of 5 or the square root of 25.

You'll dive into functions on the next section of the pre-work, but a very useful 'built-in' functions is the dir() function. You can use the dir() function, along with an argument in the parentheses, to see what other options might be available for you to use in with your imports (and later on, your variables and other objects).Many modules also contain predefined values like this example (again with math):


```python
math.pi
```

which returns the value of pi or 3.141592653589793.

What does dir(math) return?

For your use in Data Science and Machine Learning, you'll be using modules to work with files, machine learning, etc. Lastly, you can refer to modules with their own names if you need to in order to clear up any confusion caused by names. For example:


```python
import math as mt
```

This allows you to then us <b>mt</b> in the place of the module name <b>math</b>. You use the new name when we use the module as follows:


```python
mt.sqrt(25)
```

In your notebook import the following modules and experiment with some of the predefined functions within each module; use the the <a href="https://docs.python.org/3/tutorial/modules.html"> module reference </a> as a guide:
* numpy
* math

Now use numpy to establish some random data we can work with as follows:


```python
from numpy import random
import numpy as np
# uniform random numbers in [0,1]
data_one = random.rand(5,5)
```

Using the # in front of a line of code is how we comment code in Python. Do not worry about what data_one means just yet; that will be covered shortly. This should output the following:

<center><img src="images/jup2.png"></center>

This is an example of a Numpy array and something we'll be covering a little later.

Now you use a the mean function from within numpy to obtain the mean of the entire array of numbers as follows:


```python
np.mean(data_one)
```

Notice how you called <b>np</b> to reference the numpy module?

<b>Now it is your turn! Use three predefined functions with <i>math</i> to obtain information about the data stored in the numpy array; note any issues you encounter along the way as comments in your notebook. These will serve you well later as lesson learned that you have documented and can reference.</b>

<b><h1>Ok, lets dive into the basics of functions, variables and datatypes</h1></b>

<h1>Functions</h1>

Functions are a easy way to write efficient code and break your code into smaller modular pieces. This make it much easier to understand and reuse.  Almost anything in Python that does some type of task can be defined as a function and functions come pre-packaged within Python. For example: the print function does just what it sounds like it does; it prints out whatever you instruct it to print out and it takes to basic structure that all functions follow:


```python
function_name()
```

Notice the parentheses? This is where content goes that we need the function to do whatever it has been programmed work on. For example:


```python
print('I Love Python')
```

Prints out the sentence I Love Python (anything in quotes is treated as a string, but more on this in just a sec!)

We will not be writing any custom functions for our analysis here, but you are highly encouraged to experiment with writing your own!

Python has a number of functions and types built into it that are always available. They are listed <a href="https://docs.python.org/3/library/functions.html">here </a>in alphabetical order.

As was previously discovered, one of these built-in functions is the dir() function. You can use the dir() function, along with an argument in the parentheses, to see what other options might be available for you to use in your projects. For example:


```python
dir('Ben')
```

Lists all of the possible functions that I can use on 'Ben'. dir() is a great way to see all of the possible actions we can perform on various items in Python as well as a good way to also get further information about various objects in Python.

<h1>Variables</h1>

Variables are where we store things in Python and variables make it easy to reuse data. Variable names in Python can contain alphanumerical characters a-z, A-Z, 0-9 and some special characters, but normal variable names must start with a letter. Here is an example:


```python
variable_name = 25
```

This simply assigns a value of 25 to the variable named Variable_name. Here is another example:


```python
variable_name_1 = 'I Love Python'
```

What do you think happens when we now implement the print function as follows (try it yourself):


```python
print(variable_name_1)
```

    I Love Python


<h1>Datatypes</h1>

Data comes in different types (numbers, characters, etc.) so we need different ways to tell Python what type of data a variable is using so Python can treat it the correct way. Data types are not explicitly specified in Python, but variables do have a specific 'type' associated with it. The type is assumed from the value that the variable has been assigned. For example:


```python
variable_name = 25
type(variable_name)
```

Returns the int datatype for a Integer. Integers in Python are numbers without decimals.
Here is another example:


```python
variable_name = 25.0
type(variable_name)
```

Returns the float datatype for a Float, which is a number with decimals. What does dir(variable_name) return?

<b>Now it is your turn! Try the following in your own notebook:</b>


```python
var_one = 25

var_two = 25.0

var_three = var_one + var_two

print(var_three)
```

<b>Here is one more example:</b>


```python
var_one = 25

var_two = 'Hello'

var_three = var_one + var_two

print(var_three)
```

<b>What happened? Did it print out as expected? If not, see if you can research why or why not and find the solution. Be sure to bookmark where you find the answer because you'll likely be returning for other answers!</b>

There are many additional datatypes, please <a href="https://docs.python.org/3/library/datatypes.html">reference the resources</a> for more information.

<h1>Data Structures</h1>

As you have experienced, variables store one value at a time so we can use this value later, but what if we need to store more than one value? Python uses a data structure for this purpose and there are <a href="https://docs.python.org/3/tutorial/datastructures.html"> numerous data structures </a> we can use in data science. Lets start with the most basic one: Lists. 

<b>Lists</b>

A single list may contain DataTypes like Integers, Strings, as well as Objects. Lists are mutable, and hence, they can be altered even after their creation. Lists can be defined as follows:


```python
list_name = [ ]
```

Here is a real example:


```python
list_one = ['ben','ray','mike','logan']
```

The strings (they could also be numbers or even a mixture of both) are called elements. Each element in a list can be of any type and elements in ordered data structures like lists can be referenced by the physcial order of appearance, starting with '0' and moving to the right. For example: 


```python
print(list_one[1:3])
```

This returns the second and third element in the list [ray ,mike]; note that the indexes begin at 0 so [0:2] will return [ben, ray]

<b>Dictionaries</b>

Dictionaries are like lists, except that each element is a key-value pair. The syntax for dictionaries is {key1 : value1, ...}:. Here is an example:


```python
tel = {'jack': 4098, 'sape': 4139}
```

You can easily reference elements within a dictionary by simply calling their key like such:


```python
tel['jack']
```

This returns the value of 'jack', which is 4098. 

<b>Now it is your turn! Try the following in your own notebook:</b>

1. Define a variable that represents a dictionary with 5 INT elements
2. Use functions from the math module to perform three different math operations on three of the five elements; you may find it easier to define variables for the elements. Feel free to combine elements as needed. 
3. Lastly, print out you results separately.

<hr></hr>

There are numerous resources where one can get help and numerous tutorials, although many arent really for novice Python users. I feel strongly that <a href="http://greenteapress.com/thinkpython2/thinkpython2.pdf">Think Python</a> is a good starting point for Python beginners if you'd like to continue your journey there after working through this pre-work. 





```python

```
