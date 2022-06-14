# Common-Javascript-Questions
This is a guide written by myself, in my own words based on popular Javascript questions.

#1

Q: What is Javascript?

A: Javascript is a high level programming language mostly used in browsers to add interactivity to a website, it's the brain of the webdeveloper trio; html being the skeleton, and css being the rest of the body. With node it could also be used server side.

#2 

Q: What is the difference between Let and Var?

A: let is newer than Var, it came out in es6. let is block scope, so it can only be used in the function it's called unless passed on. Var is older and global, and easily resignable so you might accidently overwrite a value you don't mean too. For me when I see a repo or framework, and it uses Var I become skeptical how well mantained it is.

#3

Q: Const Vs let.

A: let can be reassigned and const can't be it. It's constant but it can be mutated if it's an array.

#4: 

Q: What is a closure

A: The child function without the parent function can call any expression or variable the parent has, but the parent can call the children's. It's good when you want to pass a single value to multiple different functions.

#5:

Q: Function declartion  vs func expression:

a function can be called before it's declared and can't be called in another function, a function expression is the opposite. the stynax is also different

#6

Q: What is Prototype Inheritence

A: Every object in javascript can easily get it's method through it's parents. so the children of said parents don't all need their own method, they just go to their parents for guidance. saves having to write the same method for every child.

#7

Q: What is Currying?

A: Currying is a partial function, meaning it calls the function argument by argument returning a new function each time till there are no more arguments instead of all at once. It's also named by it's creator Haskell Curry.

Q: What is an Arrow Function and why do we use them?

A: an Arrow function is simplier sytnax for functions, usually anonymous and if you want to use "this "in a function  normally it refers to the window object but in an arrow function is refers to the function itself. I usually call arrow functions on eventlisteners and variables.
