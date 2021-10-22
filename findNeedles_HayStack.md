# Find needles in a Hay Stack

This article helps you find number of needles in a hay stack (a packed pile of hay, typically with a pointed or ridged top). 

## Prerequisites

You'll need the following tools inorder to use the code sample below and find the count of needles in a hay stack.

* Code editor for Java programming language. This article walks you through Visual Studio 16.10.

## Creating a new project in the code editor

Follow the steps to create a new project in your code editor.

* Open your code editor of your choice or Visual studio and create a new solution 
* Rename the solution *Needles_stack*.
* Right select on the solution, select *Add*, and then select *New Item*.

## Defining variables

You'll need to define two variables to call a method later to find needles in a hay stack. Haystack is considered as a string. Needles is considered as an array of strings. You'll initialize them to zero.

```
String haystack = 0;
String[] needles = {0};
```

## Method definition

Now, you'll define the method to find needles in the haystack. 

```
public static void findNeedles(String haystack, String[] needles) {
if (needles.length > 5) {
System.err.println("Too many words!");
} else {
int[] countArray = new int[needles.length];
for (int i = 0; i < needles.length; i++) {
String[] words = haystack.split("[ \"\'\t\n\b\f\r]", 0);
for (int j = 0; j < words.length; j++) {
if (words[j].compareTo(needles[i]) == 0) {
countArray[i]++;
}
}
}
for (int j = 0; j < needles.length; j++) {
System.out.println(needles[j] + ": " + countArray[j]);
```

## Method call

You can call the method by using the below line of code. Add it below the lines of initializations of variables in the #Defining variables section.

`findNeedles(String haystack, String[] needles);`








