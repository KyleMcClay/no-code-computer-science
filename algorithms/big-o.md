---
description: Big O Notation measures relative time of algorithms completion
---

# Big O Notation

## Big O Notation

Big O Notation classifies types of algorithms by the length of time it takes to complete. 

![](../.gitbook/assets/nathan-dumlao-5hl5reicevy-unsplash.jpg)

## 🏃♀ 🤸♀ Seconds, Days or Years? 🌸 ☀ ❄ 🍁

The Algorithm will take around a 

* _Second?_ ⏲ __
* _Minute?_ ⏳ __⌛ __
* _Hour?_ 🕓 __
* _Day?_ 🌞\_\_🌚 __
* _Year?_ 🥳 __🎂 __
* _Century?_ 👶 __⚰ __
* _Millennium?_ 🗿 __
* _Eon?_ ♾ __

##  Math without the Math

Big O Notation works by approximating the total amount of steps an algorithm will take. 

lets create a list ****of the numbers 1 through 100

```text
Array = [1,2,3..99,100]
```

* O\(1\): O of 1
  * Fastest Completion Time Possible
  * Fixed Amount of Steps \(a few steps\)
  * 1 + 100
    * 2 steps 
    * Add the first and last number
* O\(log\(N\)\): O of log N
  * Extremely fast Completion Time
  * Steps continually split in half with size of data \(log of data\)
  * 50 + 75 + 88 + 94 + 97 + 99 
    * 6 steps
    * 50 = \[01-100\] Add middle of the array 
    * 75 = \[50-100\] Split array & add middle
    * 88 = \[75-100\] Split array & add middle
    * 94 = \[88-100\] Split array & add middle
* O\(N\): O of N
  * Completion time is okay
  * Steps are the size of the data \(data\)
  * 1+2+3+4+5...
    * 100 steps
    * add all the numbers
* O\(N^2\): O of N Squared
  * Completion time is slow
  * Steps are size of the data squared \(data x data\)
  * \[1+2+3..100\] + \[2+3+4..100\] + \[3+4+5..100\]...
    * 

