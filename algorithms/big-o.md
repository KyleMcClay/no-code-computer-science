---
description: Big O Notation measures relative time of algorithms completion
---

# Big O Notation

## Big O Notation

Big O Notation classifies types of algorithms by the length of time it takes to complete. 

![](../.gitbook/assets/nathan-dumlao-5hl5reicevy-unsplash.jpg)

## Seconds or Years? 🌸 ☀ ❄ 🍁

The point of Big O Notation is to give the user an idea of how fast or slow an algorithm will take to complete.

* _Second?_ ⏲ __
* _Minute?_ ⏳ __⌛ __
* _Hour?_ 🕓 __
* _Day?_ 🌞\_\_🌚 __
* _Year?_ 🥳 __🎂 __
* _Century?_ 👶 __⚰ __
* _Millennium?_ 🗿 __
* _Eon?_ ♾ __

## Math without the Math 🤔 

Big O Notation works by approximating the total amount of steps an algorithm will take. 

lets create a list ****of the numbers 1 through 100 & make a step equal a second.

```text
Array = [1,2,3..99,100]
1 step = 1 second
```

* O\(1\)➡O of 1 🚀 
  * Fastest Completion Time Possible 💯 
  * Fixed Amount of Steps \(a few steps\)
  * Example Algorithms
    * Add the first and last number
    * 1 + 100
    * 2 steps ⏲ _seconds_ 
* O\(log\(N\)\)➡O of log N 🛩 
  * Fast Completion Time💯 
  * Steps continually split in half with size of data \(log of data\)
  * Example Algorithms
    * Add middle of the array 
    * Split array in half
    * repeat 
    * 50 + 75 + 88 + 94 + 97 + 99 
    * 6 steps⏲_seconds_ 
* O\(N\)➡O of N 🚘 
  * Completion time is okay 😅 
  * Steps are the size of the data
  * Example Algorithm
    * add all the numbers
    * 1+2+3+4+5...100
    * 100 steps⏳⌛_Minutes_  
* O\(N^2\)➡O of N Squared 🤸♀🏃♀ 
  * Completion time is slow 🤢 🤮 
  * Steps are size of the data squared
  * Example Algorithm
    * add all the numbers
    * shorten array by 1 number
    * repeat
    * \[1+2+3..100\] + \[2+3+4..100\] + \[3+4+5..100\]...
    * 5050 steps🕓_Hours_

♾I_mportant to note as the size of the data grows, slow Big O algorithms run times approach infinity_ ♾ 

