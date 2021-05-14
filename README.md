# cmu-213-Intro-to-Computer-Systems
## lab0 Note:
* strlen() vs sizeof() 

>> cause we declare a string as a char pointer, sizeof() method return the size of a pointer, that is (for 64-bit computer), 8, not the size of the string.
>> 
>> Thus, it usually cause a heap overflow error as the length of the string is greater than 8.
