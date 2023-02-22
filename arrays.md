Arrays in JavaScript are used to store multiple values in a single variable. You can think of an array as a list of items, where each item has an index that identifies its position in the list. Arrays in JavaScript can contain any type of data, including strings, numbers, booleans, objects, and even other arrays.

Here's an example of an array in JavaScript:
`
var myArray = [1, 2, 3, 4, 5];
`
In addition to these basic methods, there are many other methods you can use with arrays in JavaScript. You can also loop over the elements of an array using a for loop, a while loop, or other methods like forEach() and map().
`
// loop over the elements of the array using a for loop
for (var i = 0; i < myArray.length; i++) {
  console.log(myArray[i]);
}
// loop over the elements of the array using forEach()
myArray.forEach(function(element) {
  console.log(element);
});
// create a new array by mapping each element to a new value
var doubledArray = myArray.map(function(element) {
  return element * 2;
});
`
