---
description: Big O Notation classifies types of algorithms by there speed.
---

# Big O Notation

## What is Big O Notation? ⏱ 

**Big O Notation** classifies types of algorithms by there speed. Big O Notation is used to determine how long an algorithm will take to complete.

![](../.gitbook/assets/nathan-dumlao-5hl5reicevy-unsplash.jpg)

## Seconds or Years?⏲ 

The point of **Big O Notation** is to give the user an idea of how fast or slow an algorithm will take to complete.

* _Seconds?_ ⏲ __
* _Minutes?_ ⏳ __⌛ __
* _Hours?_ 🕓 __
* _Days?_ 🌞\_\_🌚 __
* _Years?_ 🥳 __🎂 __
* _Centuries?_ 👶 __⚰ __
* _Millennia?_ 🗿 __
* _Eons?_ ♾ __

## Math without the Math 🤔 

**Big O Notation** works by approximating the total amount of steps an algorithm will take. lets create a list ****of the numbers 1 through 100 and classify different algorithms by their speed.

```text
Array = [1,2,3..99,100]
```

* O\(1\)🚀 
  * Fastest completion time possible 
  * Fixed amount of steps
  * Example: 1 + 100 __
    * _2 steps_
* O\(log\(N\)\) 🏎 
  * Fast Completion Time
  * The steps are a small fraction\(log\) of the size of the data
  * Example: 0 + 75 + 88 + 94 + 97 + 99 
    * _6 steps_
* O\(N\) 🏇 
  * Completion time is okay 
  * Steps are the size of the data
  * Example: 1+2+3+4+5...100
    * _100 steps_
* O\(N^2\) 🐌 

  * Completion time is slow
  * Steps are size of the data squared
  * Example: \[1+2+3..100\] + \[2+3+4..100\] + \[3+4+5..100\]...
    * 5050 steps

♾_Important to note as the size of the data grows, run times can approach infinity_ ♾ 

