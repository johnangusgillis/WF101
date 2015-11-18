# Lesson 1: Variables and Types


## Variables

__Variables__ are where we store things so that we can use them later.

They are defined using the `var` keyword, followed by the name of the variable:

```js
var box_for_stuff;
```

You don't have to assign anything to your variable, if you don't want to, but you will usually want to.

You can assign almost anything you want to a variable.

```js
// A String is okay.
var name = "Evan";

// A number is also okay.
var age = 25;

// This expression will be evaluated and then assigned to the variable.
var sum = 3 + 7;

// This will be a boolean (we'll learn more about those later).
var is_allowed_to_purchase_alcohol = age > 21;

// You can re-assign any variable to anything else.
var company_name = "ADKM, Inc.";
company_name = "HF Global, Inc.";
company_name = "Harry's, Inc.";

// You can even reassign variables to other types of things.
company_name = 93;
```


## Number

__Numbers__ are exactly what you think they are. You can do math(s) with them.

Numbers are truthy, except for 0. 0 is falsey.

```js
// This is just a number.
4;

// This is a mathematic expression. It will return 40.
8 + 32;

// You can assign numbers to variables.
var bar_mitzvah_age = 13;
```


## String

__Strings__ are a series of characters inside of quotation marks. Both single-quotes `'` and double-quotes `"` are totally fine.

Strings are truthy, unless it is an empty string `""`, those are falsey.

```js
// Strings can contain any characters.
"Java$crip!7";

// This is a string, not a number.
"24";

// You can assign strings to variables.
var dog_name = 'Sparky';

// You can also find out information about strings.
"Evan".length; // 4
dog_name[0] // "S"
```


## Array

__Arrays__ are simply lists of things surrounded by square brackets `[]`, and separated by commas `,`.

Any array, even an empty array, is truthy.

```js
// You can put anything you want in an array.
["Hello", 24, "list", 1.56];

// You can even put an array inside of another array.
[[0,1], [3,4]];

// You can assign arrays to variables.
var friends = ['Mike', 'Nick', 'Adam'];

// To find out what is in an array, you can use square bracket notation.
friends[1]; // "Nick"

// Arrays always start with 0.
friends[0]; // "Mike"

// You can also find out information about arrays and do things to arrays.
friends.length; // 3
friends.indexOf("Adam"); // 2
friends.push("Jeremy"); // ["Mike", "Nick", "Adam", "Jeremy"]
friends.unshift(3); // [3, "Mike", "Nick", "Adam", "Jeremy"]
```


## Boolean

__Booleans__ are the representation of truthfulness or falsehood of an expression.

There are only two boolean values: `true` and `false`.

```js
// These are the only two boolean values.
true;
false;

// You can assign booleans to variables.
var can_vote = true;

// If you have a logical expression, it will be evaluated to a boolean.
12 < 15; // false
var has_short_name = "Evan".length > 2; // true
```


## Undefined


__Undefined__ is the absence of a value.

An `undefined` variable is falsey.

```js
// You use the undefined keyword to represent undefined.
undefined;

// You can define a variable with not value. If you try to get a value from it, it will be undefined.
var love_life;

// You can assign undefined to variables (although not totally sure why you would).
var girlfriend = undefined;
```


## Null

__Null__ represents an empty value; if you get `null`, it means that the variable has been assigned `null`. There is intention in the use of `null`.

A `null` value is falsey.

```js
// You use the null keyword to represent null.
null;

// You can assign null to variables.
var dog = null;
```


## Object

__Objects__ are similar to arrays, in that they are lists, but instead of each value living at a numbered index, the values live at keys. In other languages this is called a hash or dictionary.

Any object, even an empty one is truthy.

```js
// You can put anything you want in an object.
{
    name: "Evan",
    dob: "1989-12-19",
    job: "Teacher",
    height: 198,
    interests: ["Javascript", "Star Wars", "Board Games"],
    family: {
        mother: "Jeannie",
        father: "Ralph",
        brothers: ["Max"],
        sisters: []
    }
};

// You can assign objects to variables.
var power_rangers = {
    red: "Jason",
    yellow: "Trini",
    blue: "Billy",
    pink: "Kimberly",
    black: "Zack",
    green: "Tommy"
};

// To find out what is in an object, you can use dot notation.
power_rangers.red; // "Jason"

// You can also use square bracket notation.
power_rangers["green"]; // "Tommy"

// Square bracket notation is especially helpful for when you don't know what you're looking for.
var the_nerdy_one = "blue";
power_rangers[the_nerdy_one]; // "Billy"
```
