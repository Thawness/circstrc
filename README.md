# circstrc
circstr is a c++ project from Object Oriented Programming in C++ by Robert Lafore 4th Edition

This program can be compiled on Visual C++ compiler or Borland C++ compiler. However, the Console Graphics Lite library won't compile on GCC compiler (at least it DID NOT compile the last time I tried.)

To compile this code in Visual C++ use multi-byte char. To do that:

Set Project > Properties > Advanced (or General, if you are using older versions of Visual Studio) > Character
Now set option to use Multi-Byte character set. 
Else this code won't compile. 

This program needs "msoftcon.h" and "msoftcon.cpp" files to compile on MSVC compiler.
(This program needs "borlacon.h" and "borlacon.cpp" to compile on Borland C++ compiler. Both files are given in the book in Appendix E. But I am unsure about any errors present in these files.) 

This code uploaded here also fixes the errors present in the msoftcon.h and msoftcon.cpp files given in the book to make it compilable. Without the fixes the original code won't compile and throw significant amount of errors. 


