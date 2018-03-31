# ES6 Quiz

### Date and time : 29-03-18 07:00 PM

#### Conducted in #lesson07_functions and #lesson06_syntax by @sounak07 and @Smriti
  
### How to participate?
• Include the challenge name - ES6Quiz along with your slack handle.  
• Post your answers with question numbers.  
• Ask question if u have any doubts.  
  
#### Topic: let and const  

Question-0:  
True or False - const makes variables immutable  
a:True  
b:False  
  
Question-1:  
True or False - you can redeclare the same variable using the let keyword multiple times  
a:True  
b:False  
  
Question-2:  
True or False - you can redeclare the same variable using the const keyword multiple times  
a: True  
b: False  

Question-3:  
True or false - let does not hoist  
a: True  
b: False  
  
Question-4:  
True or False - using the const keyword to declare the same variable twice results in a TypeError  
a: True  
b: False  

Question-5:  
Which one of the following keywords create block scope?  
a:try  
b:catch  
c:finally  
d:while  
e:all of the above

## Answers
Question-0:  
True or False - const makes variables immutable  
a:True  
b:False(Ans)  
*Explanation: Using const only means that the variable will always have a reference to the same object or primitive value, because that reference cannot be changed. The reference itself is immutable, but the value held by the variable does not become immutable.  
The following example shows that even though the cars reference couldn’t be changed, the array itself can indeed be modified. If the array were immutable, this wouldn’t be possible.* 
```
const cars = ['Ferrari', 'Lambo']  
cars.push('Tesla')  
console.log(cars)  // ['Ferrari', 'Lambo' 'Tesla']  
```
*A const statement only prevents the variable binding from referencing a different value. Another way of representing that difference is the following piece of code, where we create a people variable using const, and later assign that variable to a plain var humans binding. We can reassign the humans variable to reference something else, because it wasn’t declared using const. However, we can’t reassign people to reference something else, because it was created using const.*
```
const cars = ['Lambo', 'Tesla']  
var sportsCar = people  
sportsCar = 'Ferrari'  
console.log(sportsCar)  // 'Ferrari'  
``` 
*To make an object’s values immutable, use Object.freeze().*  

Question-1:  
True or False - you can redeclare the same variable using the let keyword multiple times  
a:True  
b:False  
Both correct(I forgot to include the scope….Sorry)  
  
*Explaination: cannot redeclare the same variable using the let in the same scope. But can be in different scopes.*

Question-2:  
True or False - you can redeclare the same variable using the const keyword multiple times  
a: True  
b: False(ans)  

Question-3:  
True or false - let does not hoist  
a: True  
b: False(ans)  
*let does hoist in the block scope but referencing let in the block before the variable declaration results in Reference error. The variable is in a temparal dead zone from start untill the declearation is processed.*  
More Here: [https://stackoverflow.com/questions/31219420/are-variables-declared-with-let-or-const-not-hoisted-in-es6](https://stackoverflow.com/questions/31219420/are-variables-declared-with-let-or-const-not-hoisted-in-es6)  

Question-4:  
True or False - using the const keyword to declare the same variable twice results in a TypeError  
a: True  
b: False(Ans)  

*Explanation: It causes Uncaught Syntax Error.*  
  
Question-5:  
Which one of the following keywords create block scope?  
a: try  
b: catch  
c: finally  
d: while  
e: all of the above(Ans)
