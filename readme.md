# JavaScript Array Methods 02

## assignment

1. Write short notes on the following Array
   methods with code examples 4

- filter()

  - filter methods returns a new array containing all elements of the calling array that pass the test implemented by the provided function.
  - filter method does not modify the original array

  ```js
  const numbers = [1, 2, 3, 4, 5];
  const evenNumbers = numbers.filter((number) => number % 2 === 0);
  console.log(evenNumbers); // Output: [2, 4]
  ```

  ***

- some()

  - some method returns true if any element in the array passes the test implemented by the provided function.
  - some method does not modify the original array

  ```js
  const numbers = [1, 2, 3, 4, 5];
  const hasEvenNumber = numbers.some((number) => number % 2 === 0);
  console.log(hasEvenNumber); // Output: true
  ```

  ***

- every()

  - every method returns true if all elements in the array pass the test implemented by the provided function.
  - every method does not modify the original array

  ```js
  const numbers = [1, 2, 3, 4, 5];
  const allEvenNumbers = numbers.every((number) => number % 2 === 0);
  console.log(allEvenNumbers); // Output: false
  ```

  ***

- map()

  - map method creates a new array populated with the results of calling a provided function on every element in the calling array.
  - map method does not modify the original array

  ```js
  const numbers = [1, 2, 3, 4, 5];
  const squaredNumbers = numbers.map((number) => number * number);
  console.log(squaredNumbers); // Output: [1, 4, 9, 16, 25]
  ```

  ***

- forEach()

  - forEach method executes a provided function once for each array element.
  - forEach method does not modify the original array

  ```js
  const numbers = [1, 2, 3, 4, 5];
  numbers.forEach((number) => console.log(number));
  // Output: 1
  // Output: 2
  // Output: 3
  // Output: 4
  // Output: 5
  ```

  ***

- reduce()

  - reduce method applies a function against an accumulator and each value of the array (from left-to-right) to reduce it to a single value.
  - reduce method does not modify the original array

  ```js
  const numbers = [1, 2, 3, 4, 5];
  const sum = numbers.reduce(
    (accumulator, currentValue) => accumulator + currentValue,
    0
  );
  console.log(sum); // Output: 15
  ```

  ***

- indexOf()

  - indexOf method returns the first index at which a given element can be found in the array, or -1 if it is not present.
  - indexOf method does not modify the original array

  ```js
  const numbers = [1, 2, 3, 4, 5];
  const index = numbers.indexOf(3);
  console.log(index); // Output: 2
  ```

---

# JavaScript Simple Quiz on Array Methods

![alt text](javascript-array-methods-quiz.png)
