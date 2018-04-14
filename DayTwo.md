Hi i’m Shivam and i’m back with day 2 of learn C++ on Facebook! In the day 1 i’ve explained how a simplest program in C++ works and what is it made up of. This time, I’m going to cover the most fundamental aspects of programming and C++ in contrast. I’ll discuss everything that a novice needs in order to start with programming. I’ll show you the right mindset that programmers use to solve problems creatively and a self-assessment test for you to assess yourself about the fundamentals that you’re going to learn in this message.

Since i’ve texted a few guys and they told me that they’re novice in programming. Even some of my friends get afraid to hear the word “programming”. So let me start with a bit theory and than i’ll jump over to coding part.

If you haven’t seen the Day 1 message, here it is: https://www.facebook.com/groups/freeCodeCampEarth/permalink/534259600308697/

### WHAT IS PROGRAMMING AND WHY TO LEARN IT?
Simply, programming is instructing computer to perform the task you want it to. Programming is done in form of various languages that work differently and used for various tasks. For example, the language we’re focusing on in our tutorials “The Almighty C++” is used for developing game engines, games, and also the mobile applications using various frameworks and libraries, many big software and applications that we use in our day-to-day lives are built upon C++, just to name a few: Microsoft Office, Internet Explorer (although I use it to download chrome), Adobe Photoshop, even Mozilla Firefox!

### CATEGORIZATION OF PROGRAMMING LANGUAGES:
Programming languages are categorized in something called ‘generations’. It categorizes the generic enhancements in the various computer languages that have evolved over the years.

Here’s a table that generalizes different programming languages::

* 1st generation - Machine Language [Used to program 1st generation computers]
* 2nd generation - Assembly language [low level programming language]
* 3rd generation - high-level language [includes C++, C, Java, etc.]
* 4th - query languages [various SQL]
* 5th - languages used to develop applications based upon artificial intelligence and machine learning


Well, I think it’s enough with introduction to what’s a programming language and why should you learn it. There are a lot of theory to cover and I only have 29 days left to complete C++ while giving you guys enough time to practice the concepts.

But let me tell you some theory about C++, It is a superset of C now what’s C? C is a general purpose programming language which means the applications can be written in C used for wide variety of domains and platforms. Similarly, C++ is a general purpose too. WHAT DID YOU MEAN BY C++ IS A SUPERSET OF C? C++ can run most of C code while C can not run C++ code. 
There are tons of resources available on internet that’ll explain you about difference between C and C++ languages. But for the sake of large content, let it be on the curious learners to discover their articles of choice to learn more about C++. 


I DON’T KNOW WHERE TO START!! You may try search for these queries on Google if you still don’t know where to start. 

- Basic computer science
- Introduction to C++
- What is C++
- Why learn C++

And these queries alone will give you enough data to make you understand what we’re going to learn. Anyway, if you’ll ever fall into some theoretical trap and you couldn’t find a way out, count on me for the help!

Okay now, let’s look on how to setup an environment to run your programs, it’s way simpler as it sounds, we’re going to use a compiler called DevC++ for the sake of its simplicity. You’re allowed to use any compiler of your choice, but for the beginners I recommend them to install DevC++ from this link: (https://filehippo.com/download_dev-c/) or search on Google directly. 

The installation is simple and all you need to do is click next multiple times. Now, if you’re a mac or linux user, please read the guidelines available at this link: 

MacOS: (https://w3.cs.jmu.edu/bernstdh/web/common/help/cpp_osx-setup.php)
Ubuntu: (https://www.quora.com/How-can-I-install-C++-on-Ubuntu)

 Once you’re done installing, move ahead and create a new project and than a new file. It’ll open a C++ compiler window where you can write and modify your code and run it directly.

## PROGRAM OF THE DAY:

Today, i’m going to show you basic data types and their usage. And at the end of the code you’ll find a complete explanation for you to understand that what actually is going on in there.

```
#include<iostream>
using namespace std;
int main() {
int numberOne;   //we’ve created a variable of type int to store first number that user will input  
int numberTwo;  //second variable of integer type to store second number
cout<<”enter number one”<<endl;  //shows a message on screen that asks user to enter a num
cin>>numberOne; //cin is the stdin or standard input, this takes user’s input and stores it in var
cout<<”enter number two”<<endl; 
cin>>numberTwo;
cout<<”The sum of both numbers is” << numberOne+numberTwo <<endl; // + operator adds
return 0;
}
```
First of all, if you’re not familiar of what // is than, it is used for a single line comment. A comment helps coder to mention what each element in the code does, so if the coder visits his code for around after a few months then he’ll know what each element is doing. It’s a useful practice and I would suggest you to use it in all the program that you make.

### WHY THIS HASH WITH A INCLUDE AND IOSTREAM DOESN’T CHANGE IN THIS CODE AND WHY IS IT SIMILAR TO THE CODE WRITTEN IN DAY 1?
The library that is getting included by using # (a preprocessor) includes the pre-defined functions such as cout and cin that we’re using in our code without telling the computer what cout is and how it should work. All these logical stuff are already fitted into that one library that we require before starting our program.

### WHY WE USED “INT” BEFORE numberONE and numberTWO ?
In this code the int represents integer and we used int before the names of our new variables because we wanted our variables to be of type integer, so that they can store integer values provided by the user.

### WHAT IF A USER GIVES FLOAT VALUE TO AN INTEGER VARIABLE?
When a user provides a float value, suppose, 4.0 to an integer variable, the integer variable only stores the integer part and ignores the decimal part. Such as, the output of 4.0 through an integer variable would be just 4!

### I UNDERSTAND WHAT COUT IS FROM THE DAY 1, NOW WHAT THE HELL IS “ENDL” ?
The endl after a cout statement defines compiler that it should change a line and print the next output in the next following line. If we however don’t put endl at the end of our statements, the output will mess up all in one single line. Although it will produce correct output, but it’s not a standard way to write on stdout and it messes statements as well.

### WHAT IS CIN? 
The cin or stdin or standard input is a method defined in <iostream> library that helps our program to get an input from the external user (the one who’s using the program). 
We used cin for both variables to make user enter the values separately. 

### WHAT HAVE WE DONE IN THE LAST STATEMENT? 
In the last statement we added both integers using the “+” (plus) operator. You can also use “-” (minus), “*”(multiply), and “/” (division) in place of it. Or you can write separate statements that’ll print out multiple answers using the similar variables. Such as, consider if I input two values.. Suppose 4 and 2 than numberOne will get value 4 and numberTwo will get value 2. And the output of our current program will be 4+2 = 6.

Now try to run this code on your compiler and try to make some tweaks or a basic calculator, and send me something unique that you’ve created! It’s your first self-assessment so do it and let me see what have you made!

If you have any questions, queries or suggestion than please drop down a message below =) Thank you for your support! I’ll be completing the whole session in just 29 days while producing posts daily so be sure to check and practice regularly.

I can’t promise but I’ll try my best to give you power of C++ in your hands so that you’ll be able to create programs on your own after just 29 days! Thank you!
