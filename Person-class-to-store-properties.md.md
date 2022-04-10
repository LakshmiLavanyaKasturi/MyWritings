# Tutorial to store person's detail

This tutorial walks you through the steps to create a class in Java programming language and store person's detail.

## Prerequisite

Basic understanding of Java programming language.

## Prepare your environment

In order to run code samples in Java programming language, you can set your local environment in your machine by downloading:

    * [Java Software Development Kit (SDK)](https://java.com/en/download/)
    * Code editor of your choice

---
> **Note**
>
>  If you don't wish to download SDK, you can use one of the following free online editors to run Java programs.
>
>   * [Jdoodle](https://www.jdoodle.com/)
>   * [Repl.it](https://replit.com/)
>   * [Ideone](http://ideone.com/)

---

## Get started with code

Entities are defined as classes in object-oriented programming language. Properties of an entity are stored as Class level variables. Each variable in a class has a [data type](https://www.w3schools.com/java/java_data_types.asp) associated with it. When a new object is created for an entity, a default value is assigned to each of the variables. 

The entity Person is defined as Person class. Our Person entity is defined by the properties first name, last name, and age. Here's a code snippet for the Person class.

``` java

// Class declaration
public class Person {  
    // Class level variable declaration assigning default values to the variables
        private String first_name = null; 
        private String last_name = null;
        private int age = 0; 

}

```

The properties *first_name*, *last_name* store text, hence they are defined as *String* datatype in Java. The property *age* is a whole number hence it is defined as *int* datatype in Java.

A [Costructor](https://www.w3schools.com/java/java_constructors.asp) is defined as a method that takes properties as [arguments](https://www.w3schools.com/java/java_methods_param.asp) from the caller. Constructors use [access modifier](https://www.w3schools.com/java/java_modifiers.asp) to define the scope. Below code snippet uses *public* access modifier to open the scope of the constructor to public.

```java

    public Person(String first_name, String last_name, int age) {
        
        this.first_name = first_name;
        this.last_name = last_name;
        this.age = age;
    }

```
In the code snippet above,

 - Constructor arguments are assigned to their corresponding class level variables.
 - The keyword [*this*](https://www.w3schools.com/java/ref_keyword_this.asp) is used to differentiate class level variables and constructor argument namesakes.

## Code sample

You can find the complete code sample below to store person's properties first name, last name and age. 

```java

// Class declaration
public class Person {  
        private String first_name = NULL;
        private String last_name = NULL;
        private int age = 0;

//Costructor with arguments
  public Person(String first_name, String last_name, int age) {   
        //Assign method level variables to the class level variables
        this.first_name = first_name; 
        this.last_name = last_name;
        this.age = age;
    }
```

The best practice is to implement *getter* and *setter* methods within the Person class so you can get and set the individual properties of a *Person* object created earlier. These *public* methods exist to get and set the private member variables from outside the *Person* class.

```java

// Class declaration
public class Person {  
        private String first_name = null;
        private String last_name = null;
        private int age = 0;

//Costructor with arguments
  public Person(String first_name, String last_name, int age) {   
        //Assign method level variables to the class level variables
        this.first_name = first_name; 
        this.last_name = last_name;
        this.age = age;
    }

    public void setFirstName(String firstName) {
        this.first_name = firstName; 
    }

    public String getFirstName(){
        return this.first_name; 
    }

    public void setLastName(String lastName) {
        this.last_name = lastName; 
    }

    public String getLastName(){
        return this.last_name; 
    }

    public void setAge(int age) {
        this.age = age; 
    }

    public int getAge(){
        return this.age; 
    }
}
```

Now, let's use the *getters* and *setters* created earlier, to change the *first_name* property of a *Person* object. In the sample code below, the line of code `System.out.println()` is used to print a value in the output console.

```java
public class Solution {
    
    public static void main(String[] args) {
        Person human = new Person("John", "Doe", 16);
        // output will be "John"
        System.out.println(human.getFirstName()); 
        human.setFirstName("Jane");
        // output will now be "Jane"
        System.out.println(human.getFirstName()); 
    }
}

```

To change the other properties, you can follow the same procedure as mentioned above for the *first_name*. For more information, refer to [Getter and Setter method in Java](https://www.w3schools.com/java/java_encapsulation.asp).

You can refer to the [complete implementation](https://replit.com/@Lavanya-Kasturi/Person#Main.java) with getters and setters and call to the *Person* class from a [Main](https://www.w3schools.com/java/java_classes.asp) method.

## Reference links

For more information on how to run java code using Visual Studio Code, refer to this [link](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack).