## Datatypes

_Whatever the values we are assigning to a variable is having different types. It can be number, string, boolean, array, object etc. These are datatypes in TypeScript._

1. **String Datatype:** A string is a sequence of characters wrapped within double quotes, single quotes or backticks.

```typescript
const str1 = "Hey I am a string inside single quotes";
const str2 = "Hey I am a string inside single quotes";
const str3 = `Hey I am a string inside single quotes`;
```

> Practically there is no difference between double quotes or single quotes both are string datatype only. But the string created using backticks comes up with several features such as you can write multiline strings. If we want we can use template literals that is also possible. Means we can access a variable inside the string which is not possible in double quotes or single quotes.

```typescript
let myName = "Shanu";
let strWithTemplateLiterals = `My Name is ${myName}`;
```

2. **Number Datatype:** Number datatype represents both integer and floating value in TypeScript.

> A number is always a floating point value in JavaScript or TypeScript.

```typescript
let age = 24;
```

3. **Boolean Datatype:** Boolean datatype is used to store either a value true or false. It does not have any other value.

> In TypeScript also we have truthy or falsy values similar to JavaScript.

```typescript
let isEligible = true;
console.log(isEligible);
```
