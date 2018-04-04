
# Activity : ES6Quiz 2.0

## Topic: Miscellaneous

### How to participate?
• Include the challenge name - ES6Quiz along with your slack handle.
• Post your answers with question numbers.
• Ask question if u have any doubts.

1.
```
(function(x, f = () => x) {
var x;
var y = x;
x = 2;
return [x, y, f()];
})(1)
```
a. [2, 1, 1]
b. [2, undefined, 1]
c. [2, 1, 2]
d. [2, undefined, 2]

  

2.
```
(function() {
return [
(() => this.x).bind({ x: 'inner' })(),
(() => this.x)()
]
}).call({ x: 'outer' });
```
a. ['inner', 'outer']
b. ['outer', 'outer']
c. [undefined, undefined]
d. Error

3.
```
[...[...'...']].length
```
a. 1
b. 3
c. 6
d. Error

4.
```
((...x, xs)=>x)(1,2,3)
```
a. 1
b. 3
c. [1,2,3]
d. Error

5. Is JavaScript a “pass by value” or a “pass by reference” type of language when it comes to passing function arguments?

6. What's the attribute to get the quantity of objects stored in a Set object?

a. size
b. length
c. weight
d. area

7. Is it legal or not?

a. 
```
var score = [12, 7, 14];
Math.max(...score);
```
i) Yes ii) No

b. 
```
function stuff(x::Number, y::String) { // Do stuff.. }
```
i) Yes ii) No

## Answers

1. (a) [2, 1, 1]

2. (b) . ['outer', 'outer']

3. (b) 3

4 (d) Error

5. JavaScript passes function arguments by value. In case we pass an array or an object, the passed value is a reference. This means you can change the contents of the array or the object through that reference.

6. (a) size

7 (a) Yes    (b) No
