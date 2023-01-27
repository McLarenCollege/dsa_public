# Fixing Errors

[General rules Gist](https://gist.github.com/McLarenCollege/b5aa33b214e854a04a85998af8bab7e8)


### fixing-errors-introduction
Understanding the errors


Refer to error part of [this document](https://github.com/McLarenCollege/javascript-precourse/blob/master/communication_and_fixing_errors.md)

#### Compile - time error / Syntax errors

Guess output

```js
let x = 5;
console.log(x + y);
name = 'Soham';
```

Note for Teachers:
- We can see that we are getting an error, beacuse y is not defined.
- Make them walk through reading errors. Filename, line no, caret.

### fixing-errors-average-nums
Guess output or mention the line number for the error

```js
// we are trying to calculate the the average of number in numbers in array.
let numbers = [12, 5, 17, 8, 19];
let total;
for (let x = 0; x < numbers.length; x++) {
	total = x;
}
let avg = total / x;
console.log(avg);
```
Note for Teachers:
- Ask students to mention the line number where error will occur.
- The errors in the above program are
  - `total` is not initialized with `0` so it will make the result `NaN`.
  - In the loop we are adding `x` to total, we have to add the element at index `x`.
  - In calculating the average it should be `total / numbers.length`

### fixing-errors-runtime-errors
Runtime error / (Logical errors)

Guess output

```js
function addThreeNumbers(a, b, c) {
	return a + b + c;
}
let a = 5;
let b;
let c = 10;

console.log(addThreeNumbers(a, b, c));
```
- Here we have no problem with the syntax, but the logic itself is wrong and these kind of errors are hard to debug.


### fixing-errors-with-google

Searching on Stackoverflow
Google how to join array elements in js For point 4, google how to combine array elements in js.

Query Format: query + programming language

Then mention how to pick best answer from Stack Overflow.

- When was question asked and when was it answered
- Question upvotes
- Accepted answer
- Highest voted answer

### fixing-errors-practice
Inclass challenge - Fixing errors

[Fixing errors](https://gist.github.com/McLarenCollege/7143093c69944e5390c3ad784979be7e)

