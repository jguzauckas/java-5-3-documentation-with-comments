# Documentation with Comments

As you create more and more complex programs, we want to offer some resources to anyone trying to read your code to understand your intentions and the purposes of any given section of code. We do this primarily in the form of **comments**.

---

## Comments

**Comments** are text written in a program that is ignored by the compiler and therefore not executed like other lines of code when the program is run. This means that using them, we can write in plain English like these notes are, as opposed to writing in Java.

There are three different forms of comments, each with their own purposes:
1. `/* Text Here */` Block Comments - This is meant for comments that are expected to be multiple lines (meaning there is a lot of information)
2. `// Text Here` Line Comments - This is meant for comments that can one line, short and concise.
3. `/** Text Here */` Javadoc Comments - This is one we won't use much, if ever, as it is meant for Application Programming Interface (API) documentation.

Here is an example of each of the above styles of comments from the `Comments.java` file:

```java
/* This print statement is meant to print the value 
 * of the String provided in its parentheses.
 */
System.out.println("Hello, World!");

// Prints "Hello, World!"
System.out.println("Hello, World!");

/** This is
 *  a JavaDoc
 *  comment
 */
```

While we often wouldn't use comments to talk about a single line of code, they allow us to provide details in English about a section of code to someone trying to read your work.

---

## Preconditions and Postconditions

We have seen **preconditions** and **postconditions** in many of the FRQs for this course, so what are they?

A **precondition** is a condition that must be `true` just prior to the execution of a section of program code (like a method) in order for everything to work as expected. It is important to note, that there is no expectation that the program code checks to ensure that the precondition is satisfied, so when a precondition is offered we will often just assume that it is `true` and not spend our time writing code that verifies that it is.

A **postcondition** is a condition that must always be `true` after the execution of a section of program code (like a method). When a postcondition is provided, the programmer works to ensure that it is met by the code they write. This can often involve returning a value that meets certain criteria, printing a value that meets certain criteria, or modifying the state of an object in a specific way.

The important relationship to understand here is that a programmer writes code to satisfy the postconditions when the preconditions are met.

---

## Assignment

Now that you have gone through the notes for this section, you can check out the `Try.md` and `Try.java` files to try a short assignment using this material.
