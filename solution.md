## Return Negative

```js
function makeNegative(num) {
  if (num < 0) {
    return num
  } else if (num === 0) {
    return 0
  } else return -num
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0

  for (let num of arr) {
    if (num > 0) {
      sum += num
    }
  }

  return sum
}
```

## Function 2

```js
function square(num) {
  return Math.pow(num, 2)
}
```

## Sum Arrays

```js
function sum(numbers) {
  if (numbers.length === 0) {
    return 0
  }
  let sum = 0
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i]
  }
  return sum
}
```

## Reversed Strings

```js
function solution(str) {
  let st = ''
  for (let i = str.length - 1; i >= 0; i--) {
    st += str.charAt(i)
  }
  return st
}
```
