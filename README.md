# Math Track

Welcome! We are going to use code to solve some math problems. You can use any programming language you prefer.

##The Entry Problem

Print out a list of numbers from 1 to 100 each on a new line. However, if the number is divisible by 4, print your age. If the number is divisible by 7, print your ZIP code. If the number is divisible by both 4 and 7, skip to the next number (don't print anything).

This type of problem is called a Fizz Buzz test and is common during professional interviews. If you solved it, congratualations! You know how to use conditionals and loops to solve problems, so let's see what else we can do!

###Approaching it as a Venn Diagram
![venn d](http://uvalaw.typepad.com/.a/6a00d8349d72fd69e201676818db67970b-pi)

  There are two different situations to check for:

1. If the number is divisible by 4 - let's call this A
2. If the number is divisible by 7 - let's call this B

  But sometimes we want to skip the line and sometimes we just want to print the number:

3. If both A and B - this is the overlapped part of the Venn Diagram
4. If neither A nor B - this is everything outside the circles in the Venn Diagram


