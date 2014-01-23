---
layout: post
title: "Arguments vs Parameters"
date: 2014-01-22 20:58:41 -0700
comments: false
categories: coding
---
No, no. I am not talking about proper ways to communicate or anything like that. That's a whole other coversation. Today's post is about coding.<br> 
<br>
What is it?
-----------
<br>
Parameters and Arguments are very common practices and the **foundation** of Ruby coding. This can be very confusing when new to ruby. 

    def multiply_by_11(n)   
      puts n * 11
    end

    multiply_by_11(10)
    multiply_by_11(101)
    multiply_by_11(19)   
<br>
Above is a very simple Method that I "defined" AKA named "multiply_by_11". It takes whatever number I want and multiplies it by 11. Which is the best number in the world, if I must say. For no reason, other then it is my favorite number. Okay enough jibber jabber. Let's get back to business.


###Parameter
I like to think of a parameter as a "place holder" or a "nickname" for that patucular section of code.   The (n) right after "multiply_by_11" is the parameter that is short for number. 

###Argument  
Is the actual number that I want to find the answer to. In this case there is a total of 3 arguments (10), (101), and (19). An argument is only at the end, after the method is defined and the parameter is set.   
<br>
###Conclusion
 We created the method "multiply_by_11" above, we gave it the **parameter** "n" for number, but passed it the **argument** 10,101, and 19 when we called it. When the program is ran, it will spit out the answers 110, 1111, and 209.
