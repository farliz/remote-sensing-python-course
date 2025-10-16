# remote-sensing-python-course

# Introduction
Python is a programming language used to tell computers what to do.\\
It’s known for being easy to read, powerful, and used in many areas:

- Data science
- Web development
- Machine learning
- Automation

Python works in the following way:

sourceCode --> compiler --> output

We will use the GNU/Linux terminal to execute our python's programs.

Let's to call the python termnal

## Interactive
```
$ python
Python 3.10.13 | packaged by conda-forge | (main, Dec 23 2023, 15:36:39) [GCC 12.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>

```

## by scripts
1. Open the text editor, write the code and save it as **hello.py**:

```
print("Hello world!")
```
2. Execute the script:
```
$ python hello.py
```


## Data types

| Type    | Example       | Description     |
| ------- | ------------- | --------------- |
| `int`   | 10            | integer numbers |
| `float` | 3.14          | decimal numbers |
| `str`   | "hello"       | text            |
| `bool`  | True or False | logic values    |

## Variables

A variable is a name that holds a value.

```
>>> x = 5
>>> y = -10
>>> x * y
...
>>> first_name = 'lizardo'

```
Python has an official style guide called PEP 8.
According to it, variable names should:

- Use lowercase letters
- Use underscores to separate words
- Be descriptive but short


## Operations

```
>>> a = 10
>>> b = 3

>>> a + b
>>> a - b
>>> a * b
>>> a / b
>>> a // b
>>> a ** b

```
## I/O
```
>>> name = input("What is your name? ")
>>> print("Hello,", name, "!")

```

## First program

```
print("It is my first python program!")
name = input('Type your name:\n')
print('Hello', name, '!')
```

## Keywords

```
False      await      else       import     pass
None       break      except     in         raise
True       class      finally    is         return
and        continue   for        lambda     try
as         def        from       nonlocal   while
assert     del        global     not        with
async      elif       if         or         yield

```
## Indentation

Indentation means adding spaces (or tabs) at the beginning of a line
of code to show structure — which lines belong together.

```
if age >= 18:
    print("You are an adult")

```
**The key is the ":"**   dos puntos.

## Function

A function is a reusable block of code that performs a specific task.
Instead of repeating code many times, you define a function once, and
then you call it whenever you need it.

you give it inputs, it processes them, and gives you an output.
```
------     ---------     --------
input ---> function  ---> result
-----      --------      --------
```


## dataset

We will use the USGS High Resolution Spectral Library to explore the
spectral feature of different materials. Data can be downloaded int he
following link:

[https://www.usgs.gov/centers/gggsc/science/usgs-high-resolution-spectral-library](https://www.usgs.gov/centers/gggsc/science/usgs-high-resolution-spectral-library)

