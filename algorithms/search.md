---
description: A Search Algorithm finds something
---

# Search

## What is a Search Algorithm?🧐

A Search Algorithm finds something.

![Claw Machine](../.gitbook/assets/aj-garcia-4k4tx68es50-unsplash.jpg)

## 🐌 Linear Search vs Binary Search 🚀 

🐌**Linear Search** is an algorithm which looks at each item one by one in unordered list until the item is found.

* Looking for scissors in the junk drawer✂ 
* Matching a single sock to the pair in a pile of laundry 🧦 
* Checking out the old photo album with grandma 👵 

🚀**Binary Search** is an algorithm which continually splits a ordered list in half until the item is found. 

* Finding a specific page number in a book 📖 
  * A person would look like so to find a specific page number
  * 500, 600, 580, 581, 582
  * **Not** like this
  * 1,2,3,4,5,6,7,8,9,10,11...582
* Searching for an old holiday photo in a phone🎄
  * Search by year
  * Search by month
  * Search by day

🐌**Linear Search** vs🚀**Binary Search** in a heads up comparison on the same list.

```text
Array:
[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20]

Goal:
Find the number 14

Linear Search:
1,2,3,4,5,6,7,8,9,10,11,12,13,14

Binary Search:
10,15,14
```

## 🌧BFS: Breadth First Search vs DFS: Depth First Search🌩 

🌧**BFS**: Breadth First Search algorithm _**Flows**_ in every direction evenly to find the item. In a tree data structure for example it would search for the item in all the nodes by each level\(floor\). Dropping one level & then explore all nodes, dropping one level then explore all nodes, etc..

* Tree branches growing out
* Root system expanding out

 🌩**DFS**: Depth First Search algorithm _**Strikes**_ each direction one by one to find the item. In a tree data structure for example it would search for the item by exploring a branch all the way to the bottom of a tree then trying a different branch all the way to the bottom.

* Lightning strikes

**Example Tree**

```text
        A Tree Data Structure
                Start
                  '
         -------------------
        '                   '
        *                   *
        '                   '
   ----------          ----------
  '          '        '          '
  *          *        *          *
  '          '        '          '
 ---        ---      ---        ---        
'   '      '   '    '   '      '   '
*   *      *   *    *   *      *   *
```

**BFS Example: first 8 nodes found**

```text
        Breadth First Search
                  1
                  '
         -------------------
        '                   '
        2                   3
        '                   '
   ----------          ----------
  '          '        '          '
  4          5        6          7
  '          '        '          '
 ---        ---      ---        ---        
'   '      '   '    '   '      '   '
8   *      *   *    *   *      *   *





```

**DFS Example: first 4 nodes found**

```text
          Depth First Search
                  1
                  '
         -------------------
        '                   '
        2                   *
        '                   '
   ----------          ----------
  '          '        '          '
  3          *        *          *
  '          '        '          '
 ---        ---      ---        ---        
'   '      '   '    '   '      '   '
4   *      *   *    *   *      *   *
```

