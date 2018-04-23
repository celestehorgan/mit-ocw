# Lesson 1

Lesson one goes over the basics of installing Python and using an IDE.
* The curriculum recommends using Anaconda as a package manager and Spyder as an IDE. I have chosen to use PyCharm and have used homebrew as a package manager.
* Note that the default homebrew recipe, `brew install python` installs Python 2.7. It seems that `brew install python3` is needed to install Python 3.x.
* Update: it seems as if this is a PyCharm issue and I need to tell PyCharm to install Python 3. Are Python IDE's intrinsically linked with specific versions? Feels very photoshop-y.
* After some clicking around, I figured out how to get PyCharm to recognize Python 3. The Key is to set up the Project/System Interpreter. It seemd to want the file located here: usr/local/Cellar/python/3.6.5/Frameworks/Python.framework/Versions/3.6/bin/python3.6 https://www.jetbrains.com/help/pycharm-edu/configuring-available-python-interpreters.html


## Playing with the console
This lesson has us play with Python's Console. This is accessible in PyCharm via **Tools > Python Console**.

* Python has the following operators built-in:
  * Addition: `+`
  * Subtraction: `-`
  * Multiplication: `*`
  * Division: `/`
  * Modulo: `%`
  * Power: `**`
     * To square root something, raise it to the power of 0.5.


* Imports can be done via the command line using `import <package>`. The example given to us is as follows:

```
>>> import math
>>> math.sqrt(16)

4.0
```

In PyCharm, `>>>` indicates command-line input, while output is unmarked.


## Python mechanics

* Python doesn't seem to need a runner class to do this kind of thing, which is pretty neat :)
* Python does not respect BEDMAS inherently: calculting `6+4*10` correctly requires `(6+4)*10`.
* A simple file with just `print("Hello world")` is runnable in python as-is. No containing runner method is required.
* Re: importing `numpy` and `matplotlib` – https://www.jetbrains.com/help/pycharm/installing-uninstalling-and-upgrading-packages.html


## Python Resources
* [Python 3 Docs](https://docs.python.org/3/library/index.html)
* http://www.diveintopython3.net/



# Lecture Notes

* What does thinking computationally mean?
  * When given a new challenge, how can I describe the stages of a problem to a computer to get it to solve the problem for me?
* Data structures
* Finding information via iteration and recursion
* Abstraction
* Organize and modularize code.
* Standard classes of algorithms
  * Different algorithms have different costs: expense of solving a problem.

* What does a computer do?
  * Fundamentally: it performs calculations
  * It remembers results of calculations
  * It knows about calculations built into a programming language or defined by a programmer.
