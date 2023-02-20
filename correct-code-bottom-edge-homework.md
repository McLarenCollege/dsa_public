Correct the below code such that we dont check below the bottom edge. 

```js
//correct the code below
function hasAdjacentWater(myFarm, row, col) {
   if (row > 0) {
       if (myFarm[row - 1][col - 1] === 'W') {
           return true;
       }
       if (myFarm[row - 1][col] === 'W') {
           return true;
       }
       if (myFarm[row - 1][col + 1] === 'W') {
           return true;
       }
   }
   if (myFarm[row][col - 1] === 'W') {
       return true;
   }
   if (myFarm[row][col + 1] === 'W') {
       return true;
   }
   if (myFarm[row + 1][col - 1] === 'W') {
       return true;
   }
   if (myFarm[row + 1][col] === 'W') {
       return true;
   }
   if (myFarm[row + 1][col + 1] === 'W') {
       return true;
   }
   return false;
}
let farm = [['W', 'C', 'C', 'C'], ['C', 'C', 'C', 'C'], ['W', 'C', 'C', 'C']];
console.log(hasAdjacentWater(farm, 1, 3)); // false
console.log(hasAdjacentWater(farm, 2, 1)); // true
console.log(hasAdjacentWater(farm, 0, 1));  // true
console.log(hasAdjacentWater(farm, 2, 2)); // false
```
