---
layout: post
title: "Ruby Variables"
date: 2014-01-24 18:06:33 -0700
comments: false
categories: coding
---

###What the heck is a variable?    
<br>
A variable is a place to store data. Each variable is given a unique name
An *important*  factor when coding Ruby is the scope of a variable and where it is visible in a program.    

###There are 4 main variables.     
<br>
####Global Variables     
<br>
These variables are available throughout the **ENTIRE** program. You must be careful when using global vaiables as it can cause for major headaches when trying to de-bug! Global variables are hardly used and are the least common variable. Global variables will start out with the symbol $

####Local Variables
<br>
They always begin with a lower case letter or "_" character. They are only available for certain methods within your program. Local variables do not work well with instance variables and global variables. They do not have a special character in front of them and is only available inside a method block.
<br>
####Class Variables
<br>
They belong to a specific class. Class variables start with the characters @@. They only store data for the Class and not it's decendents. Which essentially means all objects created from a particular class, share class variables. Unlike global variables, class variables must be initialized before they are used. 
<br>
####Instance Variables.
<br>
Are variables that belong to a particular instances of a class and do **NOT** effect the entire class. Instance variables start with only one @. ex: @cory vs class variables @@cory. These are the most common variables as they are flexable and allow to de-bug easier.




