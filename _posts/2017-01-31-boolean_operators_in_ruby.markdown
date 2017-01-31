---
layout: post
title:  "Boolean Operators in Ruby"
date:   2017-01-30 22:45:08 -0500
---


In Ruby, there are two boolean values: true and false.

**Syntax**

```
true => true
false => false
```

### Logical Operators

Logical operators are used to compare to boolean values. 
Ruby has three operators to compare boolean values:

* ! which represents "NOT",
* && which represents "AND"
* || which represents "OR"

For an && ("and") to evaluate to true, both values of either side of the symbol must evaluate to true. 

* true && true #=> true
* true && false #=> false

For an || ("or") to evaluate to true, only one value on either side of the symbol must evaluate to true. 

For example:

* false || true #=> true

Finally, a ! ("not") reverses the logical state of its operand: if a condition is true, then ! will make it false; if it is false, then ! will make it true. 

For example:

* !true #=> false
* !false #=> true


**Syntax**

```
// returns true if both boolean1 and boolean2 are true
boolean1 && boolean2
boolean1 and boolean2
```
```
// returns true if either boolean1 or boolean2 are true
boolean1 || boolean2
boolean1 or boolean2
```

### Comparison Operators

Comparison operators are used to test the relationship between two objects. The equality (==) and inequality (!=) operators can be used on almost any type of value where the other operators are used for numeric comparisons.

**Syntax**

```
x == y // returns true if two things are equal
x != y // returns true if two things are not equal
x <= y // returns true if x is less than or equal to y
x >= y // returns true if x is greater than or equal to y
x < y // returns true if x is less than y
x > y // returns true if x is greater than y
```

**Top-tip: The comparison operator == is distinct from the assignment operator = that is used to set a variable equal to a value. Mistaking these for each other is a common cause of unexpected behavior.
**
