### Write a program which will find all such numbers which are divisible by 7 but are not a multiple of 5,
between 2000 and 3200 (both included).The numbers obtained should be printed in a comma-separated sequence on a single line.
Hints:  Consider use range(#begin, #end) method

#### About Range function
range()
 * range(stop) : range(20) -> will take the starting number as 0, shall create a range between 0 to 20(not including 20) which can be used for iteration.
 * range(start,stop) : range(1,20) 
 * range(start,stop,step) : range(1,20,2) : step is equivalent to i+=2 
 * can iterate over a list : range(len(listName))
 
 * Python 2.0 xrange() has been modified to range() in python 3,and the range() in python 2 has been deprecated
 * Range produces the number on the fly before the iteration. previously all these numbers were produced before the loop causing huge amount of memory issue
 * Range does not work over floats but a custom function can be created for that :D