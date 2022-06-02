## CISC4080 Lab1

[other file](newFile.md)

#### Goal

* Implement bubble sort, selection sort iteratively and recursively.
* Implement linear search. 
* Familiarize with C++ STL class vector
  
Program Execution:

 

```console
$  g++ lab1.cpp -o lab1.exe  
```

The following example illustrates how your program should work.
The program first reads the length of the vector (as 5 in example below), then reads this number of integers, and push them into a vector. 
The program then reads a command (selection, bubble, rselection, rbubble), and call the corresponding sorting function to sort the vector. 
The vector after being sorted will be displayed. 
 Note that the user input are underscored. 

```console
$ ./lab1.exe
   5
   74 25 32 99 24
   selection
   24 25 32 74 99
 ```
 
 Another exuection example: 
 ```console
$ ./lab1.exe
   3
   17 5 23
   bubble
   5 17 23
```

#### General Hints: 



1. Write your main function first. 
2. Incrementally write one function and test it before moving to the next.  Please refer to the slides  on how to implement these functions.

selection: iterative selection sort function 
bubble: iterative bubble sort function
rselection: recursive selection sort function 
rbubble: recursive bubble sort function 

#### What to submit
Submit your lab1.cpp by going to the following autograder page:
https://storm.cis.fordham.edu:8443/web/project/262
You have a total of 20 submissions opportunities, and 3 submissions on a particular day.

#### Grading:

* Automatic test cases (50 pts):  5 test cases each tests one of the sorting functions. For this to work, pay attention to the following details: 
   The command used in your program needs to match with those specified in this description, i.e.,   selection, rselection, bubble, rbubble
   Before submitting your program, comment out or delete any cout statements except for the one that displaying the vector after sorting function is called.

* Handgrading (20 pts): style, comment, and logic… 
    See the autograder page for this project for details. 
