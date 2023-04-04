# 220 Notes

### push()
Add one or more elements to the end of an array and have it return the new length of the array.

`const numbers = [1,2,3]`
`numbers.push(4,5)`

### pop()
Removes the last element from array and returns that element

`const numbers = [1,2,3]`
`numbers.pop()`

### shift()
Removes the first element from array and returns that element
`const numbers = [1,2,3]`
`numbers.shift()`

### unshift()
Adds one or more elements to the beginning of the array and returns the new length of the array.

`const numbers = [1,2,3]`
`numbers.unshift(-1, 0)`

### find()
Returns the value of the first element in the array which satifies the provided condition, otherwise undefined is returned.

`const numbers = [1,2,3,4,5]`
`const foundNum = numbers.find((num) => num > 3)`

