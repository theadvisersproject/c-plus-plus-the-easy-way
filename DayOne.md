# C++ Session Day 1 of 30

Hey, I’m Shivam! I’m starting this learn code tutorial series on Facebook for free! How it’ll work? Well, I’ll be sending you messages regularly containing tutorials, code and questions for your self assessment. Just wanna make you learn languages, the easy way! If it’s possible, send me a friend request so I could create a group to add you all in! But, still, I don’t prefer groups and I would really be happy if you’d text me your doubts and suggestions separately.

I’ve found you from freeCodeCamp earth and if you don’t like me to send you messages about the first language that i’m starting ‘C++’, please text me that you don’t wanna learn. Simple right?

Let’s begin with our day 1! This is not a copy of some site or book, everything is going to be written by my own. So you may ask questions anytime and i’ll be ready to help! More accurately it’ll be great if you’ll pass me your email that you can check regularly as i’m planning to shift it to emails. For now,  let’s continue with ‘learn code on Facebook!’

DAY 1: Introduction to your first program [ through these series of tutorials let me assume you’re already a little familiar with C++ language and you know what is it used for, if not, ask me! I’ll answer you separately. ]

The hello world program! Let’s see how does this program “actually” works!
```
#include <iostream>
using namespace std;
int main() {
cout<<”Hello World”;
return 0;
}
```

## WHAT WE’RE DOING IN THIS CODE! 
We’re printing “Hello World” on stdout

## WHAT IS INCLUDE WITH A HASH? 
It’s a method through which you’re including a pre-defined library called “iostream” in your C++ program. 

## WHAT IS NAMESPACE?

Namespaces stops name related conflicts in large projects! But what exactly does the line tell C++ to do. 
### What is a namespace and what is std? std is a namespace.
A namespace is a collection of symbols.

The line tells your C++ compiler to
a) search the included parts of namespace std (i.e. iostream, iomanip) if
b) it does not find a definition of a symbol (such as (std::) cout ) before
c) declaring the symbol unknown.


## WHAT IS MAIN()? 
Main(function) is a entry point of any C++ program, which means, in other words it means that when a program is executed, the control goes directly to the main function to look for declarations of other functions around the code.

## OKAY, SO WHATS UP WITH INT? 
“Int” is a return type to the main function, which means, the main function is returning an integer type of value. See? Return 0! That’s an integer in the language of code!

Have you got the basic idea? Loved the tutorial? Wanna know anything else? Or anything? Suggestions maybe? Drop me a message ;) 

Quick note: if you're already doing C++, i'm sorry but it'll take only a few weeks for me to reach on advanced topics. Thank you!



