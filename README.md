# PYTHON-scratch-
# Language Fundamentals
Language Fundamentals Content:
  - Introduction
  - Where we can use Python
  - Features of Python
    - Simple and easy to learn
    - Freeware and Open Source
    - High Level Programming language
    - Platform Independent
    - Portability
    - Dynamically Typed
    - Both Procedure Oriented and Object Oriented
    - Interpreted
    - Extensible
    - Embedded
    - Extensive Library
  - Limitations of Python
  - Flavors of Python
  - Python Versions
- Identifiers
- Reserved Words
# Data Tpyes Content:

      -Int
      -Flot
      -Complex
      -Bool
      -Str
      -Bytes
      -Bytearray
      -Range
      -List
      -Tuple
      -Set
      -Frozenset
      -Dist
      -None
# Types: { 17 }
Data type represents the type of data represented by a variable. 
• Z=10
• X= true Data 
• X=10.5 
Dynamically typed language:
 Int
 Floa
t  Complex 
 Boolean
 String (char)
 List

 None The 3 most commonly used in-built functions  Print(x)  type(x)  id(x) addaddress of object

int data types: (0 -256)
To represents integral values o x = 10 o x = 10.5 not valid o python 2 available “long” we can represents int values in multiple ways: -1. decimal form (base -10) the allowed 0 to 9 x=12345 -2. binary form (base -2) o the allowed digits are: 0 to 1 o a=1111 1111 o b=0B1111  15 -3. octal form (base -8) o it allowes digits are 0 to 7 o The literal value is 0o o X= 0o123 o Print(x)  0o123+0b11 -4. hexa decimal form (base -16) (0- 15) a. 0 to p, A to F b. A =- 10 c. B =- 11 d. C =- 12 e. D=- 13 f. E =- 14 g. F =- 15 A to F or a to f The literal values are should be prefixed with 0x or 0X

float data types:
o number with decimal point o float values we should specify only decimal values o exponential form or scientific notation “E or e” o f=1.2e3  1200 o f=3.2E3 3200 o we can represent big values in less memory o no of values later represented “E”

complex data types:
In c, c++, java co mplex data types are not avialable o Format: a+bj o a is real part o b is imaginary part == > 10+20j ,
o j is fixed variable o for a, b both int and float values o real part use any form & imaginary part should be decimal value

Boolean data types:
Boolean values / logical values o True o False o a =20 o ``` If a > 25; == > False o True ----- > 1 o False ----- >0 o True +True ===2 o True +False===1 o False+True===0 o May be I am thinking o (True +20j) 1+20j

# String data types:
o	Any sequence of characters with in single or double quotes
o S= ‘Mahesh’ === valid o S = “Mahesh” === valid o S= “Mahesh’ ===invalid o S= Mahesh ====invalid o Multiline literales ‘’’ mahesh Mounika ‘’’  Mahesh Mounika

# Index data types:
Index have positive and negative indexes:
o S =”Mahesh” o S[0]  M o S[3]  e o S[5]  h o S[6]  error o S[-1]  h {right to left} o S[-5]  a

# slice operator:
slice == part or piece
s=abcdefghijklmnopqrstuvwxyz s[-1] == > Z



-26	-25	-24	-23	-22	-21	-20	-19	-18	-17	-16	-15	-14	-13	-12	-11	-10	-9	-8	-7	-6	-5	-4	-3	-2	-1
A 	B	C	D	E	F	G	H	I	J	K	L	M	N	O	P	Q	R	S	T	U	V	W	X	Y	Z
0	1	2	3	4	5	6	7	8	9	10	11	12	13	14	15	16	17	18	19	20	21	22	23	24	25
																									
*[ ] to retrieve part (slice) of the string*
 s=”ABCDEFGHIJKLMNOPQRSTUVWXYZ”  s[begin :end]  it returns substring from begin, then will consider from beginning of string  s[ :8]  0 to 7 ABCDEFGH  s[ 3: ] DEFGHIJKLMNOPQRSTUVWXYZ  s[ : ]  ABCDEFGHIJKLMNOPQRSTUVWXYZ  s[25] Z  s[30] index error  s[-27] index error  s[ 0:5 ] 0-4  ABCD  s[ 0:5000 ]  ABCDEFGHIJKLMNOPQRSTUVWXYZ  slice operator won’t raise any index error if the index is out of range , then it will consider up to available characters only.  s[ 9:5] index error  this is forward index  s[ 2:5] CDE s = maruthi technology output=s [0].upper()+s[1: ]  Maruthi technology output=s [3].upper()+s[1: ]  marUthi technology output=s[0:len(s)-1].upper() or [0:4],upper()  = marU output=s[0:].upper() +[1:4]’t’ .upper()  MaruT

# Mathematical operators for string:
•	s =   ‘ mah’ + ‘esh’ Mahesh
if   we apply + operator for the strings
both arguments only string type only
• s = ‘mahi’*5  mahi mahi mahi mahi mahi • int str and str * int  valid • int +str  invalid  type error • mahimahi  invalid because both arguments str • mahi+mahi  valid because both arguments str

# Fundamental data types vs immutability :

**Immutability : we can not change**
 		Once we create an object, we cannot change that content, If we are try to change the content , with those change a new object created 
        Int ,float, complex, bool, str  immutability 
1.	What is immutability concept:
2.	PVM == is intelligent
3.	A=10 ,10.5, mahi, True, False
4.	B=10 ,10.5, mahi, True, False
5.	C=10 ,10.5, mahi, True, False
6.	Print(id(10)) 1425355152
*Advantages of immutability*
1. memory utilization will be improved
2. performance will be also improved
Print(a is b)  true
	Search for an object is available or not  ?
# 	Create, search 
*FOR Example voter id creation and search*
   150 crore people in an  india
4   crore people in only Telangana
1. memory utilization will be improved
2. performance will be also improved

A,b,c,d are four people interchanging their locations
Four voters are in Hyderabad but “v” is changed him location to rajanna sircilla
Then total hyderabad  people address will be changed
 
After some days “c” was also changed to Karimnagar
Then total hyderabad  people address will be changed
 So, this problem required only 
# Immutability:
Once we create an object, we cannot change that content,
 If we are try to change the content , with those
 change a new object created 
so this is create a sircilla has been created a new object py test.py
•	python test.py
 IDLE  integrated development learning environment
 Python console
REPL tools
R  read
E  Evolve
P print
L Loop

For suppose :: print “ hello”
In this case it takes like  read,evolve,print, loop 

# Byte  data types
-byte data type represent a group of **byte numbers**==just like an array
 - for example
x=[ 10,,20,30,40,50,60,70,80,90 ]
b=byte(x)
type(b) ===> bytes
print(b[0])
10
print(b[5])
60
print(b[-1])
90
for i in b:
print(i)
10
20
30
40
...
90
print(b[100])
Indexerror: index out of range
because we are given inly 10 values(byte) in list
 # Bytearray data types
-byte array is exactly data types except that its elements can be **modified**
 --we observe one thing *byte data type & byte array data type* as well as same but byte data 
   types we cannot modified.once we create we cannot change the value, if we change the value  
   its give **Type error**
-for example:
--x =[10,20,30,40,50] --b = bytearray(x) --for in in b: --print(i) -10 -20 -30 -40

   # list data types
   - if we want to represent a group of values as a single entity where insertion order required
   - its **mutable**
   - its allows **duplicates also**
   - **growable in nature**
   - **values are should be enclosed bracket [ ]**
   - **hetogenous objects are allowed**
   - example :
   - ```
     -- list=[10,10.6,'mahesh',true,10]
     -- print(list)
     --- output [10,10.6,'mahesh',true,10]
     ```
     -- so we observe these entity of output is its duplicates are allowed
     -- heterogenous objects are allowed (HG nothing but int,float,bool,...)
     -- insertion in any order so its growable in nature
     -- Now let we discuss more examples
     --  example
     ```
     -- list =[10,20,30,40,50,60,70,80,90]
     -- list[0]
     -- output 10
     --list[-1]
     -- output 90
     -- list[1:5]
     --[20,30,40,50]
     ```
  * this list data types is Growable in nature ..i.e is our reqiurement increase or decrease of list size.*
    #  for example we append the list (means add a varaible )
    ```
    list = [1,2,3,4,5]
    list.append("mahi")
    print(list)
    output :- [1,2,3,4,5,mahi]
    ```
 # for example we append the list (means add a varaible )
list=[10,10.6,'mahesh',True,10] list.append("mouni") print(list) S C:\Users\mahes> & C:/Users/mahes/Documents/python.exe "c:/Users/mahes/OneDrive/Desktop/mahesh 1p.py" [10, 10.6, 'mahesh', True, 10, 'mouni']

  # for example we remove the list 

list=[10,10.6,'mahesh',True,10] list.remove(10) print(list PS C:\Users\mahes> & C:/Users/mahes/Documents/python.exe "c:/Users/mahes/OneDrive/Desktop/mahesh 1p.py" [10.6, 'mahesh', True, 10]


#  for example we multiply the list 

list=[10,10.6,'mahesh',True,10] list2 = list*3 print(list2) PS C:\Users\mahes> & C:/Users/mahes/Documents/python.exe "c:/Users/mahes/OneDrive/Desktop/mahesh 1p.py" [10, 10.6, 'mahesh', True, 10, 10, 10.6, 'mahesh', True, 10, 10, 10.6, 'mahesh', True, 10]```

for suppose we merging the list

list=[10,10.6,10]
list2 = [12,13,14]
list3 = (list+list2)
print(list3)
[10, 10.6, 10, 12, 13, 14]
Duplicates are also allowed in merging process double values also arrived in list*
list=[10,10.6,'mahesh',True,10]
list2 = list/3
print(list2)
TypeError: unsupported operand type(s) for /: 'list' and 'int'
addition and substraction & module are not possible in lists
Tuple data types
tuple data type is exactly same as well as list data type but one except i.e..itsimmuatable -once we create we cannot change the values -tuple is only read version of list
this is used some unchangable places whenn the programmer used in some like
for suppose we are create a Aadhar form creatrion
in this form some unchangable sentenses like country name & state name
whether its used only india so its cannot changed once we created thsi valid only in india
changable componants like candidate name ,surname,addres only movable we use LIST data
tuple elements are can be represented by () paranthesis
for examples attribute error if we added or remove the tuple
t.append("mahi")```
AttributeError: 'tuple' object has no attribute 'append'
t=(10,20,31) t.remove("mahi")

AttributeError: 'tuple' object has no attribute 'remove'
# Range data types
-range data types only represents only a sequance of numbers
-range data type is not modifiebale
-Range data type is immutable
- no. of examples in range data types we discuss below 
-Ex 1:
-range(10) then its Generate 0-9
- eg:-
r =range(10) for i in r: print(i) output :- 0 1 2 3 4 5 6 7 8 9 -suppose we have another example -range(10,20) r =range(10,20) for i in r: print(i) 1p.py" 10 11 12 13 14 15 16 17 18 19

-for example now we discuss step values like r=(10,22,3)
-we are giving end value like 22 its guven output is 10-22
-the end value is ended there while its not calculated

r =range(10,22,3) for i in r: print(i) PS C:\Users\mahes> & C:/Users/mahes/Documents/python.exe "c:/Users/mahes/OneDrive/Desktop/mahesh 1p.py" 10 13 16 19

-for example now we discuss step values like r=(10,23,3)
-we are giving end value like 23 its guven output is 10-22
-the end value is ended there while its 23 then its  calculated
r =range(10,23,3) for i in r: print(i) PS C:\Users\mahes> & C:/Users/mahes/Documents/python.exe "c:/Users/mahes/OneDrive/Desktop/mahesh 1p.py" 10 13 16 19 22

-so now we are implemting in range in list output arrived in squance
l = list(range(12)) print(l) PS C:\Users\mahes> & C:/Users/mahes/Documents/python.exe "c:/Users/mahes/OneDrive/Desktop/mahesh 1p.py" [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11] ` -we are more discuss in index topic for range

set data types
-if we want represent a values without duplicates not importance of order then we should be go there to SET data types -insertion order is not preserved -duplicates are not allowed -heterogenous objects are allowed----{ 10,10.5,"super star"} -index concept is not applicable -it is mutable collection -its growable in nature ---increase or decrease -its denoted as curly braces{} -for eg : -when we are add or remove a variable in set its not declare of order -later we adding again run it's convert to orderly

s = {100,99,10.5,True, "super"}
s.add(66)
print(s)
S C:\Users\mahes> & C:/Users/mahes/Documents/python.exe "c:/Users/mahes/OneDrive/Desktop/mahesh 1p.py"
{'super', True, 99, 100, 66, 10.5}
Note: The values True and 1 are considered the same value in sets, and are treated as duplicates:

set = {"apple", "banana", "cherry", True, 1, 2}
print(set)
output:
p/mahesh 1p.py"
{'apple', True, 2, 'cherry', 'banana'}
Note: The values False and 0are considered the same value in sets, and are treated as duplicates:

set = {"apple", "banana", "cherry", 0, False, 1, 2}
print(set)
p/mahesh 1p.py"
{0, 1, 2, 'banana', 'cherry', 'apple'}
Frozen data types:
-It is exactly same as set but only except its immutable.

so,we cannot add, removove functions.
Example
-In this example, we are creating a frozen set with the list in Python.

animals = frozenset(["cat", "dog", "lion"])
print("cat" in animals) 
print("elephant" in animals)
Output:
True
False
-now, we can try to append(add) the programme

names = frozenset(["mahesh", "suresh", "rakesh"])
print(names) 
names.append("mouni")
print(names)
output: AttributeError: 'frozenset' object has no attribute 'append'
-now, we can try to remove the programme

names = frozenset(["mahesh", "suresh", "rakesh"])
print(names) 
names.remove("suresh")
print(names)
output: AttributeError: 'frozenset' object has no attribute 'remove'
dict data types: ( key:value pair)
-if we want to represent a group of values as key-pairs -then we should go for "dict" data types

Duplcate keys are not allowed but values can be duplicated
if we try to any new key in insert an entry with duplicate key then old value will be replaced with new value
its denoted as curly braces -it is mutable cannot be preserved in order -Example:
print(Dict)
output:mahesh 1p.py"
{1: 'mahi', 2: 'mpuni', 3: 'runa'}
nested dict
-observe the image url limk:-https://media.geeksforgeeks.org/wp-content/uploads/Dictionary-Creation-1.jpg -it has a sub branches and sub branches

Dict = {1: 'devraju', 2: 'renuka', 
        3: {'A': 'maehsh', 'B': 'suresh', 'C': 'rakesh'}} 
print(Dict)
output:{1: 'devraju', 2: 'renuka', 3: {'A': 'maehsh', 'B': 'suresh', 'C': 'rakesh'}}
-some Examples add and updates

#Creating an empty Dictionary 
Dict = {} 
print("Empty Dictionary: ") 
print(Dict) 
  
#Adding elements one at a time 
Dict[0] = 'Geeks'
Dict[2] = 'For'
Dict[3] = 1
print("\nDictionary after adding 3 elements: ") 
print(Dict) 
  
#Adding set of values 
#to a single Key 
Dict['Value_set'] = 2, 3, 4
print("\nDictionary after adding 3 elements: ") 
print(Dict) 
  
#Updating existing Key's Value 
Dict[2] = 'Welcome'
print("\nUpdated key value: ") 
print(Dict) 
  
#Adding Nested Key value to Dictionary 
Dict[5] = {'Nested': {'1': 'Life', '2': 'Geeks'}} 
print("\nAdding a Nested Key: ") 
print(Dict) 
Output:
PS C:\Users\mahes> & C:/Users/mahes/Documents/python.exe "c:/Users/mahes/OneDrive/Desktop/mahesh 1p.py"
Empty Dictionary: 
{}
Dictionary after adding 3 elements: 
{0: 'Geeks', 2: 'For', 3: 1}
Dictionary after adding 3 elements: 
{0: 'Geeks', 2: 'For', 3: 1, 'Value_set': (2, 3, 4)}
Updated key value: 
{0: 'Geeks', 2: 'Welcome', 3: 1, 'Value_set': (2, 3, 4)}
Adding a Nested Key: 
{0: 'Geeks', 2: 'Welcome', 3: 1, 'Value_set': (2, 3, 4), 5: 
{'Nested': {'1': 'Life', '2': 'Geeks'}}}
None data type:
simple, None means Nothing or no value assocaited --if the value is not available,then to handle such type of cases None introduced --example:-
	print(type(None))
	mahesh 1p.py"
 <class 'NoneType'>
escape characters
\n == new line
\t === horizontal tab
\r ===  carraige return
\b == back space
.....etc

	 
