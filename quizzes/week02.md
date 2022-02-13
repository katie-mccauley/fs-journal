# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, const, and var
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A set of statements that performs a task or calculuates a value, and a function, with a paramter can take in a input and take out a output
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S- single responsible principle 
O- open closed principle 
I-Liskov subsitution principle 
I-interface segregation principle
D-dependency inversion principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
the index of pineapple is 2 because the starting position of the array starts at 0. 
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
let person = you.friends
person.push("them")
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
let num = 1
if(num > 0){
  return "number is not 0"
}else{
  return "number might be 0"
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++ becuase you want the i to increment
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model, the dom is completed in the JavaScript file becuase it is where you maniplate the structur and function of a website.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
boolean, null type, undefined type, number type, string type, arrays, objects
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
the parameter is function apples(apple)  it states the when you invoke the function, you need to input a value inside. An agrugement is when you invoke the function and the arugement is what you input inside the function
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
a primitive is a not an object, like a string, number or boolean value, but a reference value is an object 
```