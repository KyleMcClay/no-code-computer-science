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

1. _Create a new list_
2. _pull first item off of unsorted list_
3. _put it in the correct order of new list_
4. _repeat 2 & 3_

**Example:**

* \_\_💷_\[$5, $1, $10, $1, $5\]_
* _\[$5\]_💷_\[$1, $10, $1, $5\]_
* _\[$1, $5\]_💷_\[$10, $1, $5\]_
* _\[$1, $5, $10\]_💷_\[$1, $5\]_
* _\[$1, $1, $5, $10\]_💷_\[$5\]_
* _\[$1, $1, $5, $5, $10\]_ 💷\_\_

🃏 This type of sorting algorithm is commonly used in playing card games, & organizing cash in wallets🃏

## **Divide & Conquer Sort**

**Divide & Conquer Sort** is an algorithm which splits the list into smaller groups, then sorts the smaller groups, then puts the sorted small groups back together.

**Divide & Conquer Sort:**

1. _Split Lists in Half_
2. ^ Repeat Step 1 ^
3. Merge & Sort 
4. ^ Repeat Step 3 ^

**Example:**

* 💸_\[$5, $1, $10, $1, $20, $5, $1 $20\]_💸 
* _\[$5, $1, $10, $1\]_ 💵\[$20, $5, _$1, $20\]_
* _\[$5, $1\]_💵_\[$10, $1\]_💵\[_$20, $5\]_💵\[_$1 $20\]_
* 💸_Sort Lists_ 💸 
* _\[$1 $5\]_💵_\[$1, $10\]_💵\[_$5, $20\]_💵\[_$1 $20\]_
* 💸_Merge Lists_💸 
* _\[$1 $5, $1, $10\]_💵\[_$5, $20, $1 $20\]_
* 💸_Sort Lists_💸 
* _\[$1 $1, $5, $10\]_💵\[_$1 $5, $20 $20\]_
* 💸_Merge Lists_💸 
* _\[$1 $1, $5, $10, $1 $5, $20 $20\]_
* 💸_Sort Lists_💸
*  \[_$1 $1, $1, $5, $5 $10, $20 $20\]_

📕This type of sorting algorithm is commonly used when sorting big lists like the Library of Congress 15,000 book returns per day.📕 





