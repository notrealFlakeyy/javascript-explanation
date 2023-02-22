# OBJECTS

Objects in JavaScript are used to store collections of related data and functions. You can think of an object as a container that holds multiple properties, where each property has a name and a value. Properties in JavaScript objects can be any type of data, including strings, numbers, booleans, objects, and even other functions.

`
var person = {
  firstName: "John",
  lastName: "Doe",
  age: 30,
  hobbies: ["reading", "writing", "traveling"],
  greet: function() {
    console.log("Hello, my name is " + this.firstName + " " + this.lastName);
  }
};
`
