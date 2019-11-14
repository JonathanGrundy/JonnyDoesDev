---
date: 2019-11-07
title: "Var Let Const"
cover: "https://unsplash.it/400/300/?random?TheFallenTime"
categories:
  - Tech
  - React
tags:
  - test
  - something
  - tagging
---

So today i learn't `var` `let` and `const`.

Variables can be changed at any time.

Firstly `var`. `var` is a reserved key word, and you are not able to create a variable using `var`, so you must create a variable using something like:

```js
var notKeyWord;
```

All Variables must have their own unique name as this will interfere and override one another, unless they are in their own scope.

With VAR you must first declare what VAR is for example so that it doesn't return undefined.

```js
var a;
```

And then intialise it with a value such as 99.

```js
var a;
a = 99;
```

You can declare different variables on a single line, but this isn't common practise as it isn't very clear. So you would ideally create a variable as:

```js
var a = 99;
var b = 10;
var c = 1;
```

Variables can be objects, arrays and string as well as numbers.

Hoisting is essentially bringing the variable name to the top of the script declaration.

Next is Let. The main difference between let and var is scoping. So when a let key word is inside of a block scope it becomes inaccessible. Whereas a var is function scoped.

```js
{
	var a = 123;
}
console.log(a);
{
	let b = 456;
}
console.log(b);
```

This would run var a but would not run let b as this is not defined as the let function is not blocked with the console log. This would bring up an error message saying that it isn't defined.

```js
{
	var a = 123;
	console.log(a);
}
{
	let b = 456;
	console.log(b);
}
```

And then this would console log as we would expect it to as let is blocked. Also let is not hoisted so that means that if you were to create a console.log above a let variable it wouldn't be able to read it and then create an error message.

Lastly i looked at a const key word. Using a const variable means that there will be any rebinding.

```js
const a = {
	name: "Jonny"
};
```

Var is no longer commonly used as let and const have surpassed it as they are easier and less buggy then var.
