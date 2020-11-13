# Title

> Oct 22, 2020
> Getting started with programming
> Printing, reading input, variables, calculating with numbers, conditional statements and conditional operation, loops, arrays, lists, read text files, static 

Writing the command `System.out.println("...") can be taxing. In NetBeans, try to write sout on blank line (within main) and press tab (the key left to q). What happens? This shortcut may save you a lot of time in the future.

The tool can be imported for use in a program by adding the command import java.util.Scanner; before the beginning of the main program's frame (public class ...). The tool itself is created with Scanner scanner = new Scanner(System.in);.

While Loop with a Condition
So far we have been using a loop with the boolean true in its parenthesis, meaning the loop continues forever (or until the loop is ended with the break command ).

A few useful methods with strings:
string.split(" ");
string.constains("word");
String.isEmpty();
string.charAt(index);

A few useful methods with lists:
list.get(index);
list.size();
list.add(value);
list.remove(Integer.valueOf(value));
list.remove(value);
list.contains(value);

Library to read data from files: import java.nio.file.Paths;
Returns a string with the path: Paths.get("filename.extension") 
Structure: 
try(){
}catch(){
}

Static or not 
Methods in Java can be divided into two groups, based on whether they have the static modifier or not. Methods without the static modifier are instance methods. Methods with the static modifier are class methods

Instance methods are methods that are associated with an object, can process the objects variables and can call the object's other methods. Instance methods specifically CAN use the this modifier, which refers to the variables associated with the specific object, that is calling the instance method. Class methods can't use the this modifier, meaning that they can only access the variables they are given as parameters or that they create themselves.