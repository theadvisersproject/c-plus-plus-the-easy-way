### Learn C++ the easy way! Day 6: Arrays

#### Video: (https://youtu.be/lPulK2jGNc0)

#### Code: 

```
/* An array is a collection of similar type of data. Syntax, arrayName[n]....arrayName[n-1] */
#include<iostream>
using namespace std;
int main(){
	
	int array[] = {10,20,30,40,50,60};   //an array with no initial declaration and six elements

	array[5] = 42;  // replaces the element at 5th location of index (starts with 0...)
	cout<<array[5];  	// prints out the newest replaces element at 5th index location
	
	return 0;
}
```

#### Explanation: 

We've created an array of type int and declared it with no value at all (no size), so it'll dynamically allocate the amount of memory it requires during the compile time. Now, compile time is the time a compiler takes in order to change high level programming language (C++ in this case) into low level programming language (binary in all cases). 

What we are doing in this code after declaring and initializing an array of type int? Well, after completely declaring and initializing the array of type int, we're replacing a data at 5th location to the new data that we're replacing at line 15 of our code.

This way, we'll be able to replace the data of array without actually modifying the array and once we're done with replacing, we can revert back to our original set of numbers by commenting out the line 15.
