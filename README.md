# Cpp-to-Assembly-with-Loops
Convert increased complexity C++ to assembly

**Overview**
In this activity, you will again convert a simple application from C++ into assembly code. This time there are loops within the C++ code. The coding for this assignment will be performed in Codio. You will then download the file from Codio for submission, along with the completed C++ to Assembly With Loops Activity Template Word Document.

**Prompt**
Specifically, you must address the following rubric criteria:

Explain the functionality of the C++ code.
Use the C++ to Assembly With Loops Activity Template to complete this step.
The C++ file is located within the Software Reverse Engineering Playground in the Module Two file folder in Codio. It is also in the following table:

#include<iostream> 
  
using namespace std;

int main()
     {
 int num, i;
 int product=1;
 
cout<<“Enter a number:\n”;
cin>>num;
 
 for(i=num;i>0; i--)
  product = product * i;
 
cout<<“The factorial for “<< num << “is: “<< product<< endl; 
 return 0;
}
  
Convert the C++ file into assembly code.
The C++ file can be found in the Software Reverse Engineering Playground in the Module Two file folder in Codio.
Align each line of C++ code with the corresponding blocks of assembly code.
Use the C++ to Assembly With Loops Activity Template to complete this step.
Explain how the blocks of assembly code perform the same tasks as the C++ code.
Use the C++ to Assembly With Loops Activity Template to complete this step.
Consider which blocks of assembly code are skeleton code versus actual parts from the C++ program.
