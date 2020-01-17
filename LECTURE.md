# JS Errors

## Reference Errors

- When you are refering to something that in no defined;

```js
var dan = 'dan';

console.log(dale); // throw a reference error: dale in undefined;
```

## Type Errors

- You are trying to perform an operation on the wrong type:

```js
var dan = 'dan';

dan.push('dale') // throw a type error: dan.push is not function
```

## Syntax Errors

- javascript syntax is wrong

```js
var dale = 'dale';

function () {
  console.log(dale; // throws a syntax error
}
```

## Range Errors

- Your operation is out of bounds.

```js
var array = [0, 1];

console.log(array[2]); // throw a range error.

```

## try catch

- capturing errors to not stop your code from running.

```js
var dan = 'dan';

try {
  dan.push('dale);
} catch(exception) {
  console.log('cant do what you wanted');
}

```
