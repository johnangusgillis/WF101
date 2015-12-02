# Lesson 1: Operators and Logic


## Arithmetic Operators

### Standard Arithmetic `+`, `-`, `*`, `/`

These are the normal mathematic operators that you are already used to.

```js
1 + 1; // 2
2 - 2; // 0
3 * 3; // 9
4 / 4; // 1
```

### Remainder `%`

The Remainder Operator returns the remainder of dividing the two operands. Sometimes called the Modulo Operator.

```js
12 % 5; // 2
10 % 5; // 0
```

### Increment `++`

The Increment operator adds one to its operand.

```js
var x = 3;
++x; // 4
x; // 4

var y = 10;
y++; // 10
y; // 11
```

### Decrement `++`

The Decrement operator subtracts one from its operand.

```js
var x = 3;
--x; // 2
x; // 2

var y = 10;
y--; // 10
y; // 9
```


## Comparison Operators

### Equal `===`

The Equal Operator returns `true` if the operands are equal.

```js
10 === 10; // true
10 === "10"; // false
"Evan" === "Evan"; // true
[1,2,3,4] === [1,2,3,4]; // true
10 + 5 === 15; // true
```

### Not Equal `!==`

The Not Equal Operator returns `true` if the operands are not equal.

```js
10 !== 10; // false
10 !== "10"; // true
"Evan" !== "Evan Siegel"; // true
[1,2,3,4] !== [1,2,3]; // true
10 + 5 !== 15; // false
```

### Greater Than `>`

The Greater Than Operator returns `true` if the first operand is greater than the second.

```js
10 > 5; // true
10 > 10; // false
10 > 50; // false
```

### Greater Than or Equal `>=`

The Greater Than or Equal Operator returns `true` if the first operand is greater than or equal to the second.

```js
10 >= 5; // true
10 >= 10; // true
10 >= 50; // false
```

### Less Than `<`

The Less Than Operator returns `true` if the first operand is less than the second.

```js
10 < 5; // false
10 < 10; // false
10 < 50; // true
```

### Less Than or Equal `<=`

The Less Than or Equal Operator returns `true` if the first operand is less than or equal to the second.

```js
10 <= 5; // false
10 <= 10; // true
10 <= 50; // false
```


## Logical Operators

### And `&&`

The And Operator will return the first operand if it is falsey, otherwise it will return the second operand.

```js
true && true; // true
true && false; // false
false && true; // false
false && false; // false
```

### Or `||`

The Or Operator will return the first operand if it is truthy, otherwise it will return the second operand.

```js
true || true; // true
true || false; // true
false || true; // true
false || false; // false
```

### Not `!`

The Not Operator will return `false` if its operand is truthy, otherwise it will return `true`.

```js
!false; // true
!true; // false
```


## Assignment Operators

Assignment Operators assigns the value of the second operand to the first operand.

### Assignment `=`

We've already seen the simple Assignment Operator.

```js
var name = "Evan";
```

### Addition Assignment `+=`

The Addition Assignment Operator will add the value of the first operand to the second operand and set it to the value of the first operand.

```js
var x = 10;
x += 5;
x; // 15
```

### Subtraction Assignment `-=`

The Subtraction Assignment Operator will subtract the value of the second operand from the first operand and set it to the value of the first operand.

```js
var x = 15;
x -= 5;
x; // 10
```

### Multiplication Assignment `*=`

The Multiplication Assignment Operator will multiply the value of the first operand by the second operand and set it to the value of the first operand.

```js
var x = 10;
x *= 5;
x; // 50
```

### Division Assignment `/=`

The Division Assignment Operator will divide the value of the first operand by the second operand and set it to the value of the first operand.

```js
var x = 50;
x /= 5;
x; // 10
```

### Remainder Assignment `%=`

The Remainder Assignment Operator will divide the value of the first operand by the second operand and set the remainder to the value of the first operand.

```js
var x = 12;
x %= 5;
x; // 2
```
