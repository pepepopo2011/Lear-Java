# Java Tutorial
## Basic syntax
The most basic lines of working code are the following (this prints Hello Pepe on screen):
```
public class HelloYou {
  public static void main(String[] args) {
    System.out.println("Hello Pepe");
  }
}
```
"class" and the other thing inside are a must. We'll see their meaning later. Notice the ; after the command, Java doesn't interpret white space so in order to finish a sentence we need to add a ;.

Commenting:
```
//I'm a comment
/* 
I'm
a
multiline
comment
*/
```

A variable is where the data is stored. For a programmer there are different types of variable, an integer isn't the same that a rational number. The reason for that is that every type of variable is stored in different ways on the computer. The types of variables in Java are:

- **int** integer only. Operations can't usually be performed between different types of variables. The int data type allows values between -2,147,483,648 and 2,147,483,647, inclusive.
- **double** not integer numbers. The maximum value is 1.797,693,134,862,315,7 E+308 and the minimum value is 4.9 E-324.
- **boolean** Takes only two possible values-> true or false
- **char** Used for a single character e
- **String** It's considered a vector of char and it's usually useful to write words.

Syntax:
```
String name = "Pepe Popo";
int age = 14;
double desiredSalary = 9999.99;
char gender = 'n';
boolean lookingForJob = false;
```
If any variable isn't correctly defined, Java will detect the error and the compiler will stop. For example, if we define int ASD = caca.

Java is a compiled programming language, meaning the code we write in a .java file is transformed into byte code by a compiler before it is executed by the Java Virtual Machine on your computer.

A compiler is a program that translates human-friendly programming languages into other programming languages that computers can execute.

Previous exercises have automatically compiled and run the files for you. Off-platform development environments can also compile and run files for you, but it’s important to understand this aspect of Java development so we’ll do it ourselves.

The compiling process catches mistakes before the computer runs our code.


![alt text](https://s3.amazonaws.com/codecademy-content/courses/learn-java/revised-2019/Java+M1L1-+Compilation+Process+ART+409.png)

To compile a program use the command javac on the terminal and then we can execute the program with the command java.
```
javac myProgram.java
java myProgram
```


## Theoretical Background [Learn Java](https://www.tutorialspoint.com/java/java_object_classes.htm)
Java is an object oriented programming lengauge.

- **Objects** in Java posses a state and behaviour. Just like classical mechanics, the state of the objects is given by all the information about you need to know about it. For example, a particle needs its position and momentum in order to predict its next step. The "behaviour" are the set of rules that changes the state of an object. For example, the behaviour of a particle is give by its Lagrangian.  
Some objects can have simple states like an electron spin in a constant magnetic field. Its state will be defined by up or down and its behaviour will be change to spin up or change to spin down. Other real life objects could be more complex, like a radio. Its state could be given by on/off, volumme, station and its behaviour could be turn on/off, set volume to a number from 0 to 10 and set station from 1 to 3.

