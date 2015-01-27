# LanguageDay
An introduction to the Objective-C Language

##What is a computer program?
A computer program is a list of instruction given to the computer in a language it can understand. Our language for this class is **Objective-C**. A great website to learn more about Objective-C is [Ry's Objective-C Tutorial](http://rypress.com/tutorials/objective-c/)

##Objective-C Primitives
One of the primary reasons for computer languages is to do useful things with information. Historically, this has meant working with numbers and letters (as they are what humans like us use to get things done)

###Numbers
There are a few ways to represent numbers in Objective-C. Each one has specific uses. We will cover a few of the basics here.

####Integers
 An integer is a positive or negative number from -4294967295 to 4294967295 (or -2^32 -1 to 2^32 -1). You create an integer named "myInteger" like so.
 
 ```objc
 int myInteger = 32; 
 ```
 
 Use integers to represent what will be reasonably sized numbers.
 
 ####Longs
 An long is a positive or negative number from -9223372036854775807 to 9223372036854775807 (or -2^64 - 1 to 2^64 -1). You create a long named "myLong" like so.
 
 ```objc
 long myLong = 12938348573; 
 ```
 
 Use longs to represent what will be large numbers.
 
 ####Floats
  An long is a positive or negative decimal number of reasonable size (se [Ry's](http://rypress.com/tutorials/objective-c/data-types/primitives) for details). You create a float named "myFloat" like so.
 
 ```objc
 float myFloat = 129383.48573; 
 ```
 
  ####Doubles
  An long is a positive or negative decimal number of large size (se [Ry's](http://rypress.com/tutorials/objective-c/data-types/primitives) for details). You create a double named "myDouble" like so.
 
 ```objc
 double myDouble = 1291230383.4823573; 
 ```
 
