### Scala
#### From Scala Tutorial
https://www.scala-exercises.org/scala_tutorial/

***

#### Structuring Information

**Classes vs Sealed Traits**

- Classes are containers of information.
  - If you can use a *has* relationship, express it as a class.
  - "A computer *has* a motherboard, graphics card, and processor."
- Sealed traits are *algebraic data types*; like a set of possible values.
  - If you can use an *is* relationship to describe the domain, express it with
  a sealed trait
  - "A computer *is* a Linux, Windows, or iOS machine."