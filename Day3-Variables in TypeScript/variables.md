## Variables

_A variable is like a named storage in which we can store a value. This named storage then can be used over and over again in our code._

## Creation of Variables in TypeScript

_It is similar to JavaScript. The way we create variables in JavaScript same in TypeScript as well. We can use var, let and const keyword to create variables in TypeScript._

```typescript
var a = 49;
console.log(a);
let b = "Shanu";
console.log(b);
const c = true;
console.log(c);
```

> In TypeScript, data types are inferred for variables based on their initial values. Once a variable is assigned a type, it remains consistent throughout the program. For example, if a variable `a` is initialized with the value `49`, TypeScript infers it as a `number`, and only numeric values can be assigned to it later. Assigning a different data type will result in an error.

> In contrast, JavaScript is dynamically typed. This means variables are not bound to a specific type, and their values (and types) can be changed at any point during execution without causing errors.

## Rules to Declare variables

1. The variable names can contain only characters, numbers, underscore `(_)` or dollar sign `($)`. It cannot contain any other characters.
2. The first character of a variable must and should not have a digit.
3. A variable name can start with `_`, `$`or a letter.
4. TypeScript variable names are case sensitive.
5. Typescript keywords are not allowed to use as a variable name.
