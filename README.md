Good Software Metaphors
=============================
2015-10-16


Metaphors are easy to remember, and like images, they convey powerful meaning. 


Here I try to keep a book of concrete software design tips brought by metaphors whenever appear to me.

I'm a php developer, so most of my thoughts will be object oriented.



Don't assume that convention will be respected
-------------------------------------------------
2015-10-16

It would be much easier if everybody drove on the left part of the road.
But english people don't.


When your software has to deal with a convention, make a blackbox there, some kind
of hub that will be plugged by different conventions.
Do never assume that a convention will be respected.
There is no such thing as a monolithic convention, unless you create one 
for your personal use.



This is wrong:

	input based on assumed monolithic convention      -->  my software   --> output

This is better:

	input based on one convention      -->  my software   --> output
										  /
	input based on another convention  __/  


	







