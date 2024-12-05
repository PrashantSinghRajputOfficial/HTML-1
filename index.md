# JavaScript and Its Variables and Data Types

## Introduction to JavaScript : 
JavaScript ek lightweight, fast, aur powerful programming language hai jo web development mein dynamic aur interactive web applications banane ke liye use hoti hai. Is language ka istemal front-end aur back-end dono ke liye kiya ja sakta hai. Browsers jaise Chrome, Firefox, aur Edge JavaScript ko fully support karte hain.
Key Features of JavaScript:

-	Dynamic Typing: Variables ka type declare karne ki zarurat nahi hoti.
-	Event-Driven: Asynchronous events ko efficiently handle karta hai.
-	Cross-Platform Compatibility: JavaScript kisi bhi operating system ya device par chal sakta hai.
-	Rich Ecosystem: Popular frameworks jaise React, Angular, aur Node.js ke saath compatible hai.
________________________________________
### Variables in JavaScript
Variables ka use data ko store aur manipulate karne ke liye hota hai. JavaScript mein variables ko var, let, ya const keyword ke saath declare kiya jata hai.
Variable Declaration ke Types:
1.	var:
-	Function-scoped hota hai.
-	Redeclare aur update ho sakta hai.
var x = 10;
2.	let:
-	Block-scoped hota hai.
-	Sirf us block ke andar accessible hota hai jahan define kiya gaya ho.
let y = 20;
3.	const:
-	Block-scoped hai.
-	Ek baar value assign hone ke baad usse change nahi kar sakte.
4.	const z = 30;
________________________________________
### Data Types in JavaScript
JavaScript mein data ko alag-alag formats mein store karne ke liye alag-alag data types hote hain. Ye primitive aur non-primitive categories mein divide kiye jaate hain.
Primitive Data Types:
1.	String:
-	Textual data ko represent karta hai.
-	Single ya double quotes ke andar likha jata hai.
```
let name = "JavaScript";
```
2.	Number:
-	Integers aur floating-point numbers ko represent karta hai.
```
let age = 25;
```
3.	Boolean:
-	True ya false ko represent karta hai.
```
let isActive = true;
```
4.	Undefined:
-	Jab variable declare hota hai lekin initialize nahi hota.
```
let value;
```
5.	Null:
-	Intentional empty value ko represent karta hai.
```
let data = null;
```
6.	Symbol:
-	Unique aur immutable identifier ke liye use hota hai (ES6).
```
let id = Symbol("id");
```
7.	BigInt:
-	Bohot bade numbers ko handle karne ke liye use hota hai (ES11).
```
let bigNumber = 123456789012345678901234567890n;
```

### Non-Primitive Data Types:
1.	Object:
-	Key-value pairs ka collection hota hai.
```
let person = {
  name: "John",
  age: 30
};
```
2.	Array:
-	Ordered data ka collection hai.
```
let colors = ["red", "green", "blue"];
```
3.	Function:
-	Ek reusable block of code.
```
function greet() {
  return "Hello, World!";
}
```
________________________________________
### Conclusion
JavaScript ek versatile aur developer-friendly language hai jo web applications ko dynamic aur efficient banati hai. Iske flexible variables aur wide range of data types ki wajah se ye beginner se lekar professional developers ke beech popular hai. Aaj ke modern web development mein iska role bohot important hai.

