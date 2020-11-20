---
description: A Tree is a collection of nodes in a hierarchical tree structure
---

# Tree

## What is a Tree? 🌳 

A **Tree** is a collection of nodes in a hierarchical tree structure. nodes = elements

![Left or Right?](../.gitbook/assets/pexels-james-wheeler-1578750.jpg)

## Fork in the Road 🐾 

In a **Binary** \(left or right\) **Tree**,

* _Root \(current\) node_
  * _Root -&gt; Left_
    * _Root -&gt; Left -&gt; Left_
    * _Root -&gt; Left -&gt; Right_
  * _Root -&gt; Right_
    * _Root -&gt; Right -&gt; Left_
    * _Root -&gt; Right -&gt; Right_ 

The root node connects to a left node and a right node. The left node then connects to a left node and a right node. The right node also connects to a left node and a right node. and etc etc...

```text
                               Start
                                 '
                        -------------------
                       '                   '
                       A                   B
                       '                   '
                  -----------         -----------
                 '           '       '           '
                 C           D       E           F
```

## Folder -&gt; Folder -&gt; File 📁 📂 

If you are a Windows , Mac, or Linux user, think a **File System**. A file system is a **Tree** data structure. 

Using """No Code Computer Science""" folder as an example:

* _Turn on PC, while viewing the desktop_
  * \_\_🖱 _Click on the folder "No Code Computer Science"_
* _3 more folders appear:_ 
  * _"No Code Computer Science", "Data Structure", "Algorithms"_
  * \_\_🖱_Click on the folder "Data Structure"_
* _6 files appear:_ 
  * _"Primitive", "Array", "Dictionary \(Hash Map\) \(Hash Table\)", "Linked List", "Tree", "Graph \(network\)"_
  * \_\_🖱_Click on the file "Tree"_
* The text for the file "Tree" is shown
  * You Win!

😬 View the file structure on Github, not for the faint of hear 😬 

[https://github.com/KyleMcClay/no-code-computer-science](https://github.com/KyleMcClay/no-code-computer-science)

## Why Trees?🌳 🌴 🌲 

Trees are great for searching, every level deeper in the tree results in cutting the possible nodes in half \(finds the answer fast\).

* _1000 nodes -&gt; 500 nodes -&gt; 250 nodes -&gt; 125 nodes -&gt;  60 nodes  -&gt; 30 nodes -&gt; 16 nodes -&gt; 8 nodes -&gt;  4 nodes -&gt; 2 nodes -&gt; 1 node_ 

A **Tree** is useful when the data is evenly distributed throughout the tree for quick search. If a tree stored all data only on the right side, then you would have a linked list and quickly finding nodes would be extremely slow. 

