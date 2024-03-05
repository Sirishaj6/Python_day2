# Python_day2
Python - Python is a high level, interpreted and dynamically typed programming language.

High level programming language - Programming languages that can be easily understood by coders because of usage of language in building logics.

 Interpreted - In interpreted programming languages, the code is translated into machine language and executed line by line at its runtime.

Dynamically programming language-
Dynamically programming language, we do not specified any datatypes in compiling time.

statically programming language-
Statically programming language is a predefined function 

Datatypes- 
INTEGER 
STRING
BOOLEAN 
FLOATING 

Type conversation- 
we specified type conversation for knowing the Datatype 
example  :

a=1
print(a)
print (type(a))
b=string(a)
print=(b)
print(type(b))

<'class int'>
<'class string'>


Day_3

* Why Index starts from a zero value?
* Index having a off-site distance from 1st value to itself.
* Index starts from zero value

 example :[t,e,l,u,g,u]- >Index

From 1st element 't' to itself value is zero.
from element 't' to  'e' value is 1
from element 't' to  'l' value is 2
from element 't' to  'u' value is 3
from element 't' to  'g' value is 4
from element 't' to  'u' value is 5


Lists: Group of data should store in lists
and list are called as heterogeneous datatypes.
we can store any datatypes in the lists 
like: number, string,integer etc..
we can add 1 value for variable also and we use ".append " for adding elements in the lists

Real-life example are- we can store multiple items in fridge 


example : 
number = [1, "hello", true ]
print(nums)
nums.count("1")
nums.append("apples")
nums.index(1)
nums.remove("hello")

output> 
>2
> 1 ,hello,true ,apples
>0
>1,true

Arrays :
Arrays are homogeneous datatypes we can store a same datatypes in an Array.
Dynamic Arrays :
we do not specified any datatypes in compiling time.
static Arrays:
is a predefined function 


Day-4

variables:naming convention 
* variables are starts with alphabets and underscore 
* we can't declare with numbers and special characters
* we declare variables with meaningful names
* variables are like memory container

Mutable and Immutable Data structure:

Mutable: we can access multiple things at a time 
Immutable: we can't access multiple things or applications at a time or same time,if we access multiple applications in a same time it will be hanging or deadlock the application. this situation is also called a deadlock condition
That's why we use a Immutable data structure in these situations.

#DAY_5 

Time complexity is a measure used in computer science to describe the amount of time an algorithm takes to run as a function of the length of its input. It provides an estimate of the maximum time required for an algorithm to complete its execution, usually expressed in Big O notation. This helps in understanding how the algorithm's performance scales with increasing input size.

2)In time complexity why ignore constants :-

In time complexity analysis, constants are ignored because the focus is on understanding how the algorithm's performance scales with input size. Constants represent fixed factors that do not change with the size of the input. Since the goal is to analyze how the algorithm behaves for large inputs, these constant factors become less significant as the input size grows. Ignoring constants allows for a more generalized understanding of the algorithm's efficiency and scalability.

3)why only consider largest component time complexity in a algorithm:-

In time complexity analysis, we typically focus on the largest component because it gives us an upper bound on the runtime behavior of the algorithm. This largest component, often referred to as the dominant term, is the part of the algorithm that grows the fastest as the input size increases. Since we're interested in understanding how the algorithm's performance scales with larger inputs, we focus on this dominant term to get a general understanding of the algorithm's efficiency. Other terms or constants may exist, but they become less significant as the input size grows, so we prioritize the dominant term for simplicity and clarity in analyzing algorithm efficiency







 
