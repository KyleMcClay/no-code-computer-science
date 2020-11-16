---
description: A Dictionary is a collection of key value pairs
---

# Dictionary \(Hash Map\) \(Hash Table\)

## What is a Dictionary? 📖 

A Dictionary is a collection of key value pairs, meaning in order to access the elements \(value\) a corresponding element \(key\) must be known. 

![Cluster Mailboxes Requiring a Key](../.gitbook/assets/tim-evans-uf-c4u1usfq-unsplash.jpg)

## Cluster Mailbox 🗝 📥 📤  <a id="cluster-mailbox"></a>

To access, obtain, add, or remove mail \(value\), the information needed is the correct key \(key\). 

## Key -&gt; Value 🔐 

Keys act as unique identifiers to their values

* house key -&gt; opens house 🗝 -&gt; 🏠
* car key      -&gt; opens car       🔑-&gt; 🚗 

similar to a physical key that says, "Honda" on it vs a key with a "house" carved into it. If i wanted to access my house I would only need to find my house key which looks very different from my car key. 

## IRL Hypothetical 🛣 

A customer goes into local automotive store, for a popped tire, not remembering the date when they bought the tire, or the warranty offered. The customer asks an employee if the popped tire is covered. The employee proceeds to look up the information associated with the customer. Normally the **Key** provided is a name and phone number, information \(key\) the employee can access the ****account aka **Value** and find relevant information about the tire purchased. 

## Hash??? 🚭 

What is meant by hash? A **Hash** is a math-magical way to turn your key into a number \(index\). Once the hashing is complete for the key the dictionary is basically an array. This number \(index\) is used to access the value \(item\) in the array.

* _This is hard to understand: key -&gt; \(hashing\) -&gt; number -&gt; gives access to value_ 😕 

## Array vs Dictionary __🍎 🍊 

**Arrays** are used when the data needs to be ordered by number.

* _Recipe for Apple Pie: 1. ingredients 2. bake 3. eat_📔 
* _Finish times of a race: 1st place: 10 mins 2nd place: 11 mins, 3rd place 11.1 mins_ 🏁

**Dictionaries** are used when the data does not need to be ordered by number and instead can be accessed by name. 

* _Recipe book: key = 'Apple pie' value = recipe, key = 'meatloaf' value = recipe, key = 'pizza' value = recipe_ 📔 
* _Race contestants: key = 'Kyle' value= \[full name, age, weight, race number, starting time, finished time\]_ 🏁 

## Set 🦄 

A **Set** is a collection of items with no repeated items. Each item in the set is a special & unique unicorn, just like you the reader. The reason sets are apart of the dictionary section is because sets are implemented as dictionary unique keys without values. 

* _Ash Ketchum the pokemon trainer is trying to collect at least one of all the pokemon._ 

_Adding the same pokemon to Ash's pokedex does not change the set._

