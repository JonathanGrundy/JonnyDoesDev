---
date: 2019-11-11
title: "Learning to Debug early on"
cover: "https://unsplash.it/400/300/?random?TheFallenTime"
categories:
  - Tech
  - React
tags:
  - test
  - something
  - tagging
---

I have learnt very early on that debugging is a vital skill to attain whilst learning to be a developer. It is because you need to know what problems maybe and how you can fix them.

Firstly there is print statements, this is where the computer will tell you itself there is a bug. It determines whether a function is being used correctly or what data is being used. They are available in near enough every programming language.

When you print out in Javascript it will print out the object in a nestible and searchable structure on Chrome. Making it easier to find the bug causing the error.

Next there is error handling, many programming languages provide a way of "catching" common errors in programmes. So the programme throws an error instead of crashing it will be caught and some code can be run that will respond to the error.

If your code keeps crashing at a particularly spot you can surround the code with:

```js
try {
	dangerousCode();
} catch (error) {
	print(error);
}
```

Then investigate the error that gets returned.

The third way to fixing a bug is commenting things out. If you are working on bit of code that you know has a bug, you are able to go through line by line commenting out each one to locate the buggy line.

There is debugging tools also, which can be found in different browsers such as Chrome of Firefox. With these debugging tools you can add breaks to places in their code. It means you can run your code in a debugging mode and the programme will stop when it hits the break. That means you can step through the code line by line examining the values of all variables.
