//=========
# Afternoon speech
===
## Tips for reading code
One way to improve programming skills is Read Great program.
Most of us have to read lots of code that perhaps unstructured
, or maintained by dozens of people, etc
And the question is: How to read and understand some code like 
that?
That is something I want to share with you!

### Build and run the program
The first tip: try to build and run the program. Being able to 
build the program yourself will help you find out which external 
libraries are being used, what compiler and linker options are in 
effect, etc. And if you can build a debug version of the program, 
you can step through the code with the debugger

### Find the high-level logic (I mean MAIN function)
Most of program have a main loop -- find it. Starting with main 
function (entry point). Find down how the program initializes 
itself and terminate. Sometimes we don't have
"main". But they still have some entry point. Try to find it.

### Draw some Flowcharts
That are a horrible design tool - quite time-consuming but they 
can be useful when
analyzing program flow. You cannot keep all that information
in your head. So draw some flowcharts or state diagrams while
you are reading.

### Examine Library Calls
If the program use external libraries, examine the library calls
and read the documentation for those calls.

### Search for key words
Using IDE which you use to open project to search entire source tree
for occurrences of words associated with what you want to know. For 
example, if you want to figure out how/where the program allocate the
memory you can search with key words: alloc, malloc, free and I think 
you may get a lot of hits, but that's not a bad thing -- just focused 
reading of the code will result.

Often-useful words for C/C++ programs are "main", "abort", "exit", 
"catch", "throw", "fopen", "creat", "signal", "alarm", "socket", "fork", 
"select". Other words are useful in other languages. 

### Write UnitTest
This will help you prove to yourself that you understand what the code 
is supposed to do, what it actually does, and that you understand its 
limitations. Making it simple because It just help you to understand code
while you are reading.

### Comment the code
Making a backup original source code. While you are reading the code. You
can read comments or if having some important lines of code, try to 
comment it. It will helpful later. It also help you to find bugs if any.

### Clean Up the Code
If you realize some lines of code need clean up, try to Rewrite it in 
different ways, or a more pleasing way. You may have noticed on Wiki 
that while refactoring or reworking a page, you come to understand the 
material much deeper than just by reading it. Code is not much different 
from writing.

Therefore, when reading code, reformat it as you go along. Realign spaces. 
Comment the Code, as it says above. Fix out of date comments (vis ThePalimpsestEffect).
Fix spelling. Make the code conform to the coding standards. Usually code is 
written somewhat hastily, so having someone come along later to make the 
code look professional is also another benefit.

But, if you do a lot of changes, run the UnitTests! Breaking things isn't 
necessarily something to be afraid of. By finding the hairier parts of the 
system and the dependent parts of the system (often those you won't expect), 
you come to grok the system.  

### Conclusion
---
With some tips above I have just share with you. I Hope that it helpful for 
you while reading a big program. Thanks for you listening.

### Summary
1. Build and Run program
2. Examine library call
3. Search for key words
4. Find high-level Logic
5. Draw some flowcharts
6. Write UnitTest
7. Comment the code
8. Clean up the code
      == END ==
