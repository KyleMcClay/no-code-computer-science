---
description: A Dictionary is a collection of key value pairs
---

# Dictionary \(Hash Map\) \(Hash Table\)

## What is a Dictionary? 📖 

A **Dictionary** is a collection of key value pairs, meaning in order to access the elements \(value\) a corresponding element \(key\) must be known.

![Cluster Mailboxes Requiring a Key](../.gitbook/assets/tim-evans-uf-c4u1usfq-unsplash.jpg)

## Cluster Mailbox 🗝 📥 📤  <a id="cluster-mailbox"></a>

To access, obtain, add, or remove mail \(**value**\), the information needed is the correct key \(**key**\). 

## Key -&gt; Value 🔐 

**Keys** act as unique identifiers to their **values**.

* house key -&gt; opens house 🗝 -&gt; 🏠
* car key      -&gt; opens car       🔑-&gt; 🚗 

Similar to a physical key that says, "Honda" on it vs a key with a "house" carved into it. If i wanted to access my house. I would only need to find my house key which looks very different from my car key. 

## IRL Hypothetical 🛣 

A customer goes into local automotive store, for a popped tire, not remembering the date when they bought the tire, or what the warranty was. The customer asks an employee if the popped tire is covered. The employee proceeds to look up the information associated with the customer. Normally the **Key** provided is a name and phone number, the employee can access the ****account aka **Value** and find relevant information about the tire purchased. 

## What is Hashing??? 🚭 

A **Hash** is a math-magical way to turn your dictionary key into a number.

**Hashing** is used because computers can find values faster using numbers \(hashed keys\) instead of letters \(keys\). 

* key -&gt; \(hashing\) -&gt; number -&gt; value
* 🗝-&gt; ➕➖ -&gt;    🔢    -&gt; 🔓 

## Array vs Dictionary 🍎 🍊 

**Arrays** are used when the data needs to be ordered by number.

* Recipe for Apple Pie: 1. mix ingredients 2. bake 3. eat📔 
* Finish times of a race: 1st place: 10 mins 2nd place: 11 mins, 3rd place 11.1 mins 🏁

**Dictionaries** are used when the data needs to be accessed by name. 

* Recipe book: key = 'Apple pie' value = recipe, key = 'meatloaf' value = recipe, key = 'pizza' value = recipe 📔 
* Race contestants: key = 'Kyle' value= \[full name, age, weight, race number, starting time, finished time\] 🏁 

## Set 🦄 

A **Set** is a collection of items with no repeated items in the set. Each item in the set is a special & unique unicorn, just like you the reader. The reason sets are apart of the dictionary section is because sets are dictionary keys without values. 

* Ash Ketchum the pokemon trainer is trying to collect at least one of all the pokemon.  

🐉Adding the same pokemon to Ash's pokedex does not change the set🐉

