### Day 5 of C++ the easy way: more data types: string and bool, variable naming conventions

Since we’re now enough sure about how basic stuff works, let’s put our two days into learning some more data types, variable naming rules! If you don’t know anything about any term that I just mentioned then worry not. We’ll cover everything in brief. I’ve planned to move the array and “for” loop session in day 6 where all we’re going to do is to have fun with code! 


Let’s start our day, with another data type i.e., String 
Now, as I’ve discussed earlier about some pre-built datatypes, string is one among them. The string data type is defined in a standard library <string> , it’s easy to remember and a lot useful.

#### Now, why was string made?
String data type gives the properties of storing a “string” or “sequence of characters” in a variable. 

#### Ok. So why don’t we use string in place of char? 
A char stores a single character while a string stores group of characters. 

#### So, how do I utilize a string in my program?
How to make a proper code by utilizing a string?

Well, let’s look into an interesting example of String, that I learned in my first semester. Let’s make the program say “Hi, How are you” to the person whose name is going to be inserted by the user. Got it? Well, let’s look into code and than i’ll explain the working.
```
#include<iostream>
#include <string>
using namespace std;
int main()
{ string Name;
cout<<"Enter your name: "<<endl;
cin>>Name;
cout<<"Hi, How are you? Mr. "<<Name<<endl;
return 0;
} 
```
Here, we’ve included the standard library that contains string into our program using <string> in <>. Than, as usual we’ve used a namespace standard and created our main function.

Now, we’ve created a variable Name of type string.  And asked user to enter his name. Than, what we did is we’ve used a standard input function of C++ to store the input of user into the Name variable. Once the input is stored, we created another cout statement that said, “Hi, how are you” and than the variable “Name”. So the output turned into: Hi, How are you? Mr. Shivam

See? This is how easy it is to work with strings in C++! Try to make some of your own and let me know if you did fall into some trouble.

So, our next data type is bool! Well, bool.. Is different amongst them all. It doesn’t stores anything floating or not even strings, but it has the most important property! It has only two input and outputs. Either a true or a false. Either a 0 or a 1 but not anything else! Not 2 or 3! Let me explain, if a boolean value is assigned to an integer, true turns into 1 and false turns to 0. While if a integer value is assigned to a boolean, 0 becomes false and non-zero values becomes true.

We could use bool in our code as,  

```
bool available = true;
bool alive = false; 
```

I hope now your concepts are well clear about all the data types that we’ve discussed so far. And if not, message me on Facebook! 

You’ve learned a few new skills, try implementing them to build anything. I would love to see any kind of code from you in my messages. Just keep learning. 

So, as we’ve covered all the data types here’s an important thing left, what are variable naming rules? Well, C++ defined some rules about how you should name a variable and how you should not. This includes the following: 
 

* Make sure the variable name that you’re just going to assign is not previously defined in C++ like, you should not name an integer type variable “int”. 
* Use camelCase or PascalCase, these two are cases to define variables, the camelCase contains the first letter of starting word as small and all other starting words capital. In pascal case, every starting letter is capital. Eg MyLastHorseWasWhite 
* Don’t use special characters such as @,#,!,& in a variable name.
* Try not to use numbers in the beginning of a variable, put it in middle or somewhere in last.
* Use underscore to separate two words in a variable name. Don’t use ‘-’ to do so. Eg. Canned_Milk
* Most of the times we put in our code variables with the name of “a”,”aaaaa” etc. We should use proper defining name of variables, as if I have to create a variable that defines color of my dog I would not name it “d” instead i’ll be a good guy and follow the naming conventions to name the variable something like “myDogColor” or anything related. (It’s not important, however it’s a good practice) 

I’ll be creating day 6 the same day as i’m running a day back. But don’t worry, it all will be end in time. 

Got any questions? Ping me.
