A farm has several rows of crops C and some water outlets W. You are given a farm in form of nested array like

```js
let farm = [['W', 'C', 'C', 'C'], ['C', 'C', 'C', 'C'], ['W', 'C', 'C', 'C']];
```
A farm is said to be `well hydrated` if each crop has at least one adjacent water outlet.

Write a function isWellHydrated which takes in the farm and returns true if it is `well hydrated`, otherwise false.

```js
function isWellHydrated(myFarm){
 // write your code here
}
let farm = [['W', 'C', 'C', 'C'], ['C', 'C', 'C', 'C'], ['W', 'C', 'C', 'C']];
console.log(isWellHydrated(farm)); // false
farm = [['W', 'C', 'C', 'C'], ['C', 'C', 'W', 'C'], ['C', 'W', 'C', 'W']];
console.log(isWellHydrated(farm)); // true

```
