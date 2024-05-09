# Array practice

Identify the time complexity of each of these functions with a 1 sentence
justification for your answer. Assume `arr` is an array of length _n_.

## `arr.push()`

Time complexity: O(?) -> O(1)
Space complexity: O(?) -> O(n)
Justification: 
Time COmplexity: The push method is O(1) time complexity since it does not iterate through an array. 

-Space complexity: And O(n) space complexity since it is increasing memory to insert elements at the end of an array.

[push on MDN][push]


## `arr.pop()`

Time complexity: O(?) -> O(1)
Space complexity: O(?) -> O(1)
Justification: 

- Time copmlexity is O(1) since we are not iterating over an array.
-Space complexity is O(1)since we are decreasing the array and maintaining the same space.


[pop on MDN][pop]

## `arr.shift()`

Time complexity: O(?) -> O(n)
Space complexity: O(?) -> O(1)
Justification:

- Time complexity is either O(n) since the method removes from the beginning of an array.
- Space complexity is O(1) since an array is still maintaining the same amount of space.


[shift on MDN][shift]

## `arr.unshift()`

Time complexity: O(?) -> O(n)
Space complexity: O(?) -> O(n)
Justification: 

- Time complexity of unshift is O(n) since it is adding one item to an array resulting in a linear increase in operation.
- Space complexity is O(n) since the method is increasing the amount of memory required inside of arrays.


[unshift on MDN][unshift]

## `arr.splice()`

Time complexity: O(?) -> O(n)
Space complexity: O(?) -> O(n)
Justification: 

- Time complexity is O(n) since it is iterating over array elements.
- Space complexity is O(n) since it returns a new array with more mem. 

[splice on MDN][splice]

## `arr.slice()`

Time complexity: O(?) -> O(n)
Space complexity: O(?) -> O(n)
Justification: 

- Time complexity is O(n) since method iterates over array elements.
- Space complexity is O(n) since it returns a new array and require more mem.

[slice on MDN][slice]

## `arr.indexOf()`

Time complexity: O(?) -> O(n)
Space complexity: O(?) -> O(1)
Justification: 

- Time complexity is O(n) since it iterates over an array to find a specified index.
- Space complexity is O(1) since it does not add new memory for locating an index.

[indexOf on MDN][indexOf]

## `arr.map()`

Time complexity: O(?) -> O(n)
Space complexity: O(?) -> O(n)
Justification: 

- Time complexity is O(n) since it iterates over an array's elements
- space complexity is O(n) sinc eit creates a new array.

[map on MDN][map]

## `arr.filter()`

Time complexity: O(?) -> O(n)
Space complexity: O(?) -> O(n)
Justification: 

- Time complexity is O(n) since it is iterating over array elements.
- Space complexity is O(n) since it creates a new array.

[filter on MDN][filter]

## `arr.reduce()`

Time complexity: O(?) -> O(n)
Space complexity: O(?) -> O(1)
Justification: 

- Time complexity is O(n) since the method is iterating.
- Space complexity is O(1) since memory is decreased to return one value.


[reduce on MDN][reduce]

## `arr.reverse()`

Time complexity: O(?) -> O(n)
Space complexity: O(?) -> O(1)
Justification: 

- Time complexity is O(n) since it iterates over an array's elements.
- Space complexity is O(1) since it does not create more memory for array elements.
[reverse on MDN][reverse]

## `[...arr]`

Time complexity: O(?) -> O(n)
Space complexity: O(?) -> O(n)
Justification: 

- Time complexity is O(n) since it iterates over values to create an array.
- Space complexity is O(n) since spread creates more memory to store array elements.

[spread on MDN][spread]

[push]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push
[pop]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop
[shift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift
[unshift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift
[splice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice
[slice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice
[indexOf]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf
[map]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
[filter]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
[reduce]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce
[reverse]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse
[spread]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax
# Big-O-Helpful-Practice
