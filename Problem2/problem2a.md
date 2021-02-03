Problem \#2a "Tables and Structures" 
=======================

Outcomes 
--------

-   Load data in MATLAB
-   Format the data into `structs` and `tables`
-   Use indexing to filter data

Problem 
-------
Instead of working with many separate but related arrays, you can construct `tables` and `structures` of related data not of the same type. Today, I want you to load data about the periodic table into MATLAB and manipulate that data as a `table` and as a `struct`. You should then construct a script that uses indexing to sift through the data and answer various questions about it.

1. Create and save a new script called `periodic2.m`
1. Write a script that:
* Imports your file `PeriodicTable.csv` (the same file from Problem 2). How you import the file is your choice.
* Transforms (if needed) the data into a table
* Answers the questions below. (You should NOT be hardcoding the answers in the program, but writing code that answers them. You should NOT be typing out the answers in comments at any point).
1. In the same script, repeat Step 2 using a struct to store the data.

Questions 
-------

1. How many elements are denser than water?

2. How many elements float in mercury, in their natural form, AND also have an atomic mass greater than 100? List those elements in alphabetical order.

3. What is the average atomic weight of elements discovered in the 20th century? List those elements' symbol.

3. What are the elements with the most isotopes? List the top ten elements by number of isotopes.

4. *Questions to be considered*: Are tables or structures easier to deal with when processing data? When would using structures be advantageous?

