# Value and Reference
When we work with variables we need to understand well the concept of *Value* and *Reference*.

## Value
Every time we work with a value we aren't overwriting the variable value, we just have the value itself handed to the *class*, *method* or *attribute* itself.

![](../../../Img/j_17.png)

In this example, we passed the value that `myValue` holds, but it doesn't affect the value of `myValue` itself.

## Reference
When we use the reference, we use the memory direction where the variable is stored, so in this the value will be modified.

![](../../../Img/j_18.png)

In this other example, we create a instance of a Player class, we check the initial level and then pass the reference of the object to a method. We finally check that the level of that instance was altered.

## How to know if it's a reference or value pass
Well, it's easy to know this, by default if the variable you pass is a primitve (*integer*, *string*, *double*, *boolean*) it will be a value pass.

In other hand it'll be a reference pass.

[Go Back 🏠](./README.md)