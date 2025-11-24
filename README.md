# Multi-Level Array and Object Destructuring

## Problem Statement
Use multi-level destructuring to extract name, city, and street name from an array of people objects. Return strings in the format:

`"Alice lives in New York on Broadway"`

## Given Data
```js
const people = [
  {
    name: "Alice",
    address: {
      city: "New York",
      street: { name: "Broadway", number: 123 }
    }
  },
  {
    name: "Bob",
    address: {
      city: "Los Angeles",
      street: { name: "Sunset Boulevard", number: 456 }
    }
  }
];
