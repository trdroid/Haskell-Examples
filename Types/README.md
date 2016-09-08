# Types

### Features

Haskell's type system has the following features

* Compile time type checking
* Type inference 

**Compile time type checking**

In Haskell, the type of every expression is inferred at compile time. 

The benefits are 

* It offers safer code, as expressions involving incompatible types are flagged as errors during compile time rather than until run time which involves debugging program crashes.

**Type Inference**

Haskell can infer type based on an expression. In languages like Java and C#, the type has to be explicitly mentioned.

**Explicit Types**

Explicit types in Haskell are specified with an uppercase first letter in its name. Eg. *Char*, *Bool*

### Examining Types

The types of expressions can be examined in GHCi using the *:t* command.

To examine the type of an expression, the *:t* command can be used in the following way

```
ghci> :t <expression>
```

**Understanding the output**

```haskell
ghci> :t 'c'
'c' :: Char
```

The operator :: is read as "has type of". The output of the above example can be read as: 'c' has type of *Char*.

```haskell
ghci> :t False
False :: Bool
ghci> :t 3 == 4
3 == 4 :: Bool
ghci> :t True
True :: Bool
ghci> :t 3 == 3
3 == 3 :: Bool
```

The above ouputs can be read as

* *False* has type of *Bool*
* The expression 3 == 4 has type of *Bool*
* *True* has type of *Bool*
* The expression *3 == 3* has type of *Bool*

```haskell
ghci> :t "Hello World!"
"Hello World!" :: [Char]
```

The above output can be read as: The string "Hello World!" has a type of *a list of Char*'s. The square brackets ([]) denotes a list.

