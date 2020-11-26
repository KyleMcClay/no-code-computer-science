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
3. Put item in the correct order of new list
4. Repeat 2 & 3

**Example:**

* 💷\[$5, $1, $10, $1, $5\]
* \[$5\]💷\[$1, $10, $1, $5\]
* \[$1, $5\]💷\[$10, $1, $5\]
* \[$1, $5, $10\]💷\[$1, $5\]
* \[$1, $1, $5, $10\]💷\[$5\]
* \[$1, $1, $5, $5, $10\] 💷

🃏 This type of sorting algorithm is commonly used in playing card games, & organizing cash in wallets🃏

## **Divide & Conquer Sort**➗⚔🌈

**Divide & Conquer Sort** is an algorithm which splits the list into smaller groups, then sorts the smaller groups, then puts the sorted small groups back together.

**Divide & Conquer Sort:**

1. Split Lists in Half
2. ^ Repeat Step 1 ^
3. Merge & Sort 
4. ^ Repeat Step 3 ^

**Example:**

```text
                Array
                  '
          -------------------
         '                   '
       Half                Half
         '                   '
    -----------         -----------
   '           '       '           '
Quarter    Quarter   Quarter    Quarter 
   '           '       '           '
    -----------         -----------
         '                   '
   Sorted Half         Sorted Half
         '                   '
          -------------------
                  '
            Sorted Array
```

📕This type of sorting algorithm is commonly used when sorting big lists like the Library of Congress 15,000 book returns per day.📕 

