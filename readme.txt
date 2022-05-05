aout() 1.0
----------

A function to output a character.

The usage is as following:

  char v;
  
  v = 'c';
  
  aout (v, 1);
  
Another possible call would be

  aout (v, 0);
  
So the prototype of the function  aout()  is

  aout (char character, bool newline);
  
character  is the character to show on the screen,

newline    1 = a newline- character is placed behind the shown character
               further output will be placed in a new line
			   
           0 = no newline- character will be placed, further outputs 
		       occurr in the same line
  



Version history
---------------

Version 1.0

Initial version

