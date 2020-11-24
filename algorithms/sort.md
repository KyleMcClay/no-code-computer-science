---
description: A Sorting Algorithm creates order
---

# Sort

## What is a Sorting Algorithm? 🌈 

A **Sorting** Algorithm takes a disorder group and orders the group.

![Livraria Lello](../.gitbook/assets/pexels-ivo-rainha-1261180.jpg)

## Insertion Sort 💵 💴 💶 💷 

**Insertion Sort** is an algorithm which goes through a list item by item, putting each new item in the correct order.

**Insertion Sort:**  

1. Create a new list
2. Pull first item off of unsorted list
3. Put it in the correct order of new list
4. Repeat 2 & 3

**Example:**

* 💷\[$5, $1, $10, $1, $5\]
* \[$5\]💷\[$1, $10, $1, $5\]
* \[$1, $5\]💷\[$10, $1, $5\]
* \[$1, $5, $10\]💷\[$1, $5\]
* \[$1, $1, $5, $10\]💷\[$5\]
* \[$1, $1, $5, $5, $10\] 💷

🃏 This type of sorting algorithm is commonly used in playing card games, & organizing cash in wallets🃏

## **Divide & Conquer Sort**

**Divide & Conquer Sort** is an algorithm which splits the list into smaller groups, then sorts the smaller groups, then puts the sorted small groups back together.

**Divide & Conquer Sort:**

1. _Split Lists in Half_
2. _^ Repeat Step 1 ^_
3. _Merge & Sort_ 
4. _^ Repeat Step 3 ^_

**Example:**

* ➡= **Sorting**
* \*\*\*\*➕= **Merging**
* _$5, $1, $10, $1, $20, $5, $1 $20_
  * _$5,  $1_  ➡ _$1, $5_  
  * _$10, $1_ ➡_$1, $10_ 
  * _$20, $5_ ➡$5, $20 
  * _$1, $20_ ➡$1, $20
* _$1, $5_ ➕_$1,  $10_ 
  * \_\_➡_$1 $1, $5, $10_
* _$1, $5_ ➕_$20, $20_
  * \_\_➡_$1, $5, $20, $20_
* _$1 $1, $5, $10_➕_$1, $5, $20, $20_
  * ​➡_$1 $1, $1, $5, $5 $10, $20 $20_

📕This type of sorting algorithm is commonly used when sorting big lists like the Library of Congress 15,000 book returns per day.📕 





