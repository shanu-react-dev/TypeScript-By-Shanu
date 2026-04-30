## TypeScript

_Typescript is a programming language which is built on JavaScript. Unlike JS TypeScript has many features which allows us to write less error prone code with some exciting new features._

_TypeScript is a superset of JavaScript which means it contains all features of JavaScript plus it has some additional features like interface and access modifier etc. which is currently not available in the current version of JavaScript. It makes writing JavaScript easier and more powerful with additional features which it provides._

_However we have one disadvantage here, TypeScript code can not be executed directly by JavaScript runtime like browsers._

## Why TypeScript??

_TypeScript has additional features, which does not exist in current version of JavaScript. It makes writing JavaScript code much easier faster and less error prone._

## How can we execute TypeScript code??

_TypeScript is not just a programming language. It is also a very powerful compiler which can run and compile TypeScript code into JavaScript._

_When we run a TypeScript code, it gets compiled to JavaScript code, which can be executed by JavaScript runtime like browsers/Node JS._

## How can TypeScript use new features which is not available in JavaScript and at the end it gives us regular JavaScript code??

_The TypeScript compiler compiles the new features of TypeScript to JavaScript using some work arounds in JavaScript._

_TypeScript transpiles modern or non-JavaScript features into equivalent JavaScript patterns that existing runtimes can execute._

_In typescript we can write the code in nice and simple way and when it is compiled or transpiled then it will be converted into JavaScript complex code using some existing features of JavaScript._

_TypeScript is strongly typed which allows you to specify a type of the variable explicitly on the other hand JavaScript is dynamically dtyped._

```JavaScript
//JavaScript code
const num = 10;
const str = "Hello Shanu";
let val = 100;
val = "Hii Sundari";
```

```typescript
//TypeScript code
const num: number = 20;
const str: string = "Hello";
let val: number = 24;
val = "Sundari"; // error
```

## What is the advantage of TypeScript being strongly typed??

_Well it gives us an opportunity of identifying any errors in our code earlier before we run or compile the code. It also allows us to identify and fix any bugsat the earlier stage of our development._

## Advantages and DisAdvantages of TypeScript

| Advantages of TypeScript                                                                                                                                                | Disadvantages of TypeScript                                                                                                                                    |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| We can explicitly specify the data type of a variable, which helps catch errors and avoid bugs while writing code                                                       | The only Disadvantage with TypeScript is, it has one extra step of compiling the TypeScript code to JavaScript, before it gets executed by JavaScript runtime. |
| TypeScript provides features like interfaces and access modifiers, which are not available in current version of JavaScript                                             |                                                                                                                                                                |
| TypeScript also has meta-features like decorators, which you will learn about in detail in this course                                                                  |                                                                                                                                                                |
| TypeScript is also highly configurable. So you can fine tune the TypeScript compiler to your requirement to make sure that it behaves in the way you want it to behave. |                                                                                                                                                                |
