## Javascript Function Basics

### Objectives

* Define and invoke functions that take 0-2 arguments and return a value.

* Describe the following terms as they relate to Javascript functions: name, parameters, arguments, return, invoke

* ~~Solve world hunger~~

### Agenda

* **I do**
  Explain why functions are important and
  show an example of a function and break it down


* **We do**
  Work through a function as a class and
  describe the parts of the function as we go


* **You do**
  Create three functions that take a varied amount of arguments

### Why Functions?

There are many reasons why functions are important to learn. Functions are the building blocks of a larger application. In Javascript and other languages, functions provide the ability to reuse code.

### The Anatomy of Functions

Let's take a look at a function:

```
function subtract(numOne, numTwo){
   return numOne - numTwo;
}
```

This function takes in two numbers and returns the second number subtracted from the first number. But there are a number of different parts here to know and understand!


**Name**
In order to use a function we must first define it. The first step is to use the javascript keyword `function` and then follow that with what you want to name the function. It is generally a good idea to have the name of your function describe what the function does

**Parameters**
In functions we follow our name with an open and closed parenthesis `()`. With our `subtract` function we have `(numOne, numTwo)` inside of the parenthesis! These are called parameters. In short, parameters are what we name the variables that we pass in to our function.

**Return**
Inside most functions we will have the Javascript keyword `return`. `return` ends a function and spits out the value that is on the right side of the expression. In our `subtract` function, our return looks like `return numOne - numTwo` so our function is returning the value of the first number we pass in minus the second number we pass in. *Note* that once you hit a return in your function, you will not keep going further down the function.

### Let's use a function

Here is how we would `invoke` our function:

```
subtract(2, 1);
```

**Invoke**
To invoke a function you use the *name* of the function and the open and close parenthesis `()`.

**Arguments**
With a function that has parameters, we should give two arguments inside of those parenthesis similar to how we defined parameters earlier. Where parameters were the name of what we would pass in, arguments are the actual values we pass in at the time of invocation. A quick note, since we passed in 2 and 1 as our values `numOne` would equal `2` and `numTwo` would equal `1`.

###Assignment###

1. Create a function named `helloWorld` that takes 0 arguments and returns `"Hello, World!"`.

2. Create a function named `hello` that takes in 1 argument and returns `"Hello, (Your argument here)"`. Note that these must be strings.s

3. Create a function named `sum` that takes in 2 arguments and returns the sum of the two arguments passed in. Note that these must be numbers.
