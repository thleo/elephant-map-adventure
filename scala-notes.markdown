### Scala
#### From Scala Tutorial
https://www.scala-exercises.org/scala_tutorial/

***
#### Definition and Evaluation
**`def` vs `val`**
`def` can be an expression that will be *evaluated* when called
`val` will evaluation a RHS expression and set that as the value of the variable

#### Structuring Information

**Classes vs Sealed Traits**

- Classes are containers of information.
  - If you can use a *has* relationship, express it as a class.
  - "A computer *has* a motherboard, graphics card, and processor."
- Sealed traits are *algebraic data types*; like a set of possible values.
  - If you can use an *is* relationship to describe the domain, express it with
  a sealed trait
  - "A computer *is* a Linux, Windows, or iOS machine."

#### Higher Order Functions

- an *Anonymous Function* is simply a function that when written, has no name.

e.g.:
``` Scala
(x: Int) => x * x * x
```
  
#### Standard Library

- This section of the tutorial uses a magical character known to man as the underscore (\_)
  - In the first exercise, `\_` is used as a placeholder for parameters
- There are multiple applications/uses for the magical underscore, but this is the relevant use not explained
  - *More here*: http://ananthakumaran.in/2010/03/29/scala-underscore-magic.html
  - And *here*: https://stackoverflow.com/questions/8000903/what-are-all-the-uses-of-an-underscore-in-scala
  
- Optional values
  - Use `option` to specify either `None`  or `Some[x]` when asked for a value. 
    - If there is a value given, use `Some[x]` to express what that value should be/how it should be operated on
    - If no value is given, return `None`
  - [Official Documentation: Optional Values](http://www.scala-lang.org/api/2.12.3/scala/Option.html)
  
  #### Syntactic Conveniences
  
  #####  [Super awesome cheatsheet](https://docs.scala-lang.org/cheatsheets/)
  
  **aka** ***syntactic sugar***
  
  `new` {...} | defines anon fxn
