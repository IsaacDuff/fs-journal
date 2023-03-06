# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let and cont are the words used for declaring a variable. 
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
the definition of a function is the beginning part. Its the name and the paramaters within the ()
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
single responsiblity, open closed, liskov sub, interface segregation, dependency
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Pineapple is in the 2nd position. Arrays count up but they start at 0 instead of 1 so it is in the 2nd spot. 
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push (them)
console.log (you)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
a conditional if something that controls how javascript will run. such as an if statement

if(quantity > 0) {
  console.log(item)
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i dont remeber the exact name but it is the spot that tells the for loop what to do, so here we would add quantity ++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM means your document aka your html. First you apply your code to your js and then it accesses the html to apply it. 
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
string, number, bigin, boolean, undefined, null, symbol, object, element
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
an argument is the actual value that is passed into the function when it is called. A parameter is what is placed within the function to show that they will be an argument and hold the position of that value. 
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
a primitive value is just a thing. so it holds the exact value of what it has ben set to and only pulls or pushes that exact thing. a reference value is one that is pulled from a set of values. it changes depending on its previous factors and will always check its value. 
```