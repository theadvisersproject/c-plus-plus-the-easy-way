# Day 3 and 4 out of 30

This message has turned into a little longer as it contains content of two days, including day 3 and day 4.. As i failed to write and send you all the day 3 lesson, i’ll be including both of them into this message. Thank you for accepting the delay =)

### WHAT ARE WE GONNA COVER TODAY?
Since we’ve been playing with “int” from a long time, don’t think that its the only data type available to us! Today, i’m gonna show you all the data types that we have in our hands to utilize in our code, their byte sizes and which data type is utilized for what purpose. IN DAY 4, we’ll look at types of variables: local variables and global variables.

### WHAT ARE DATA TYPES?
Data types defines type of data that is going to be defined in a variable. Suppose, I want a variable to hold a character type data, so instead of initializing it with “int” in beginning I would, as I know all the data types, would go for “char” (char myCharacter = “S”) and that’s it! 

### SO.. WHAT DATA TYPES ARE AVAILABLE TO ME TO UTILIZE IN MY PROGRAM?
Here’s the list! Go through it to learn about them all! And in last, i’ll show a basic code that’ll define sizes of each data type in terms of bytes. 

### NOW WHAT THE HELL IS A BYTE?
Well, a byte is a group of 8 bits.
### WHAT IS BIT?
A bit is either a 0 or a 1, consider it as either a off state or on state. 
### WHY DO WE USE 0 & 1 AND NOT 2-3-4?
Well.. Our computer only understands 0s and 1s, it converts decimal numbers such as 2,3,4….. A million… or billion… or … anything into forms of 0s and 1s and than understands it. 

### OK ENOUGH! LET’S GET OVER TO DAY 3!

All right, so the list of data types that are available to you is as follows: 

There are total 3 categories of data types: (a) Integer, (b) float, (c) Character

### WHATS IN INTEGER?

Integer data types are used to store whole numbers. Whole numbers are the ones which doesn’t has any number after the decimal point. Not even a 0. 
The data types that fall into this category are as follows, along with their memory sizes and range (a range is the maximum or minimum value a data type defined variable could hold)

- int  → 2 bytes → range: -32768 to 32767
- Short int → 2 bytes → range: -31768 to 32767
- Long int → 4 bytes → range: -2147483648 to 2147489647
- Signed int → 2 bytes → range: -31768 to 32767
- Unsigned int → 2 bytes → range: 0 to 65535

The difference between signed int and unsigned int is that signed might contain a negative value but unsigned couldn’t, as it only stores values ranging from 0 to 65k.

These data types are differentiated on the scale of their range and base. You can use any data type of your choice into your code. For example, int money = 130000; 

PS. Sometimes I might not be able to cover everything in one text due to time limitations as I’ve to complete one topic in one night and than send it to you all separately, it takes time. But, if you’ve gone through the text and failed to understand anything than just drop me a message and i’ll try to get back with a solution as soon as possible.

### FLOATING POINT 
Floating point number is a number with a decimal value, such as, 3.0 , 3.14, 5.67, 9.10 etc.

- Float → 4 bytes → Range: 3.4E-38 to 3.4E+38  (E = Exponent)
- Double → 8 bytes → Range: 1.7E-308 to 1.7E+308
- Long double → 10 bytes → 3.4E-4932 to 1.1E+4932

Ex. float pi = 3.14;

### CHARACTER
If you’d ever like to store a character value and not a number, you’re gonna use character type of datatype.

- char → 1 byte → -128 to 127
- unsigned char → 1 byte → 0 to 255
- signed char → 1 byte → -128 to 127

### WHY THE HELL ARE WE DEFINING RANGE IN TERMS OF NUMBERS WHILE CHAR IS USED TO STORE CHARACTER TYPE OF DATA?
Computers don’t understand characters, they understand numbers, some binary numbers! So, ASCII has made a standard that defines characters and special characters in terms of numbers, they’re called ASCII numbers. And these are the ASCII numbers that we’re defining in the range of our character data types.

### IS THAT ALL?
Yes. I’ve mentioned all the pre-defined data types available for you to utilise. However, the list doesn’t ends yet. We can also utilize some user defined data types.

### WHAT ARE USER DEFINED DATA TYPES?
User defined data types are defined by a programmer in his code. This facility of creating our own data types are suitable for object oriented programming. If you’ve ever done C before, you might have faced struct and union that does the same work, THEY HELP CREATE USER DEFINED DATA TYPES!

[SOME ADVANCE REFERENCE AND NOT OF THIS DAY] HOW DOES USER DEFINED DATA TYPES ARE SUITABLE FOR OBJECT ORIENTED PROGRAMMING?
The base of object oriented programming are “classes (we’ll look into deeper into classses in future texts)”. Classes are similar to struct in C but you can’t create an object of a struct.

 NOW, WHAT’S NEXT? Well, let’s look at our last category of data types!

### DERIVED DATA TYPES
Derived data types are the ones that are “derived” from basic data types. Derived data types doesn’t create any new data type but actually it adds some sort of functionalities in basic data types. In C++ they are of 3 types:

- Arrays
- Functions
- Pointers

We’ll look deeper into arrays, functions and pointers in their separate lessons in upcoming days.

# Day 4 / 30

## TYPES OF VARIABLES

Since, we’ve seen variables since the beginning of our tutorials. At day 2 we’ve declared a variable of type int and asked user to input a number that’ll go and save in that variable.

Now, consider variables as buckets that stores only those fishes which them buckets are labeled of. Now, consider a simple example, what happens when you insert a floating type fish into a bucket that stores integer type fishes only? This is just to test your understand so far, if you’re able to recognize old concepts then that’s fine! You’re on the right learning curve. And if not, text me what you think would be the right answer and why’d you think so?/

### There are two types of variables: 
* Global Variables
* Local Variables

### GLOBAL VARIABLES: 
Those variables that can be accessed and used anywhere in the whole program are called global variables. They’re not declared inside any function, you’ll know why in the local variables.

Example of a global variable through a simple code:
```
#include<iostream>
Using namespace std;
Int num = 25;
Void display(){


Cout << “number is :”<<num;
}

Int main(){
display();
Return 0;
}
```
```
OUTPUT 
// Number is : 25
```
As you can see in the above example, we’ve defined a variable outside of any function and we’ve utilized it inside a new function called display. This is how global variables work.

### LOCAL VARIABLES:
local variables are the variables created inside a block, such as some function or a control statement block (we’ll discuss about what control statements are in probably day 5 or in future texts). 

This kind of variables can only be accessed or used inside the block in which they’re defined. 

### FOR EXAMPLE:

```
#include<iostream>
Using namespace std;

Int thisFunction(){
	Int num = 11;
	cout<<num;
}

Int main(){
	cout<<”hey”;
	cout<<num;
	Return 0;

}
```
```
OUTPUT
// error: num was not declared in this scope
```
In this example we’re accessing a variable defined in thisFunction() into main function. By doing this, an error will generate because ‘num’ is a local variable and it can only be used iniside thisFunction() 
