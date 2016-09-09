# Functions

In Haskell, a function can be 

* an infix function
* a prefix function

### Defining functions

A function is defined by specifying its name followed by a list of parameters. The parameter list is followed by the = operator and the body of the function.

### Calling Functions

**Calling an infix function**

An infix function is called by specifying the function name sandwiched between its parameters.

```haskell
ghci> 5 + 10
15
```

The '+' in the following example is an infix function as it is sandwiched between two numbers.

**Calling a prefix function**

A prefix function is called by specifying the name of the function followed by its parameters.

```haskell
ghci> min 5 10
5
ghci> max 5 10
10
ghci> min 5.9 3.14
3.14
```

### Function calling Precedence


