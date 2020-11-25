# Lists

When we cant to handle many values, we can't just declare all the variables. Maybe if there were only 3 variables we could declare the three of them but what if we have 1,000 variables? or 50,000?

Getting to the point of managing a huge number of variables makes the standard variable declaration useless, that's why we have *ArrayLists*.

> ArrayList is a pre-made tool that makes easier the job of creating a list in Java.

### How to use ArrayList

To use ArrayList we must first include the command `import java.util.ArrayList;` in our file.


Once imported, you can create a list using `ArrayList<type> list = new ArrayList<>();`

![](../../../Img/j_12.png)

You can add some value to the list by using `<listName>.add(<value>);`, and you can get the value from the list by using `<listName>.get(<id>);`


![](../../../Img/j_13.png)

### Iterating over a list