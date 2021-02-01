# Problem 2: Importing/Exporting

##Outcomes 

- Load data in MATLAB 
- Use typecasting to convert data types

##Problem 

The tedious part of any program is inputting data. Luckily, using the function `input` is not the only way of obtaining data to use in your programs; there are a plethora of functions: `textscan`, `load`, `readtable`, etc. In this assignment, I want you to write a script that loads data about the periodic table into MATLAB. Once the data is loaded, your script should convert any values to the most convenient data types - strings and numeric types. Finally, export a subset of the data to a new file.

1. Create the repository `p2-[username]` by following the link: [GitHub](https://classroom.github.com/a/A499YDjC). You will save your work here.
1. Modify the script called periodic.m so that it:
 a. Loads the data in PeriodicTable.csv into MATLAB. You choose the best method.
 a. Ensures that all text fields are strings and all numeric data are appropriate numeric types.
 a. Exports a subset of the data to a new file called smallperiodictable.csv. Specifically the columns: Atomic Number, Element, Symbol, Atomic Weight, Atomic Radius, Electronegativity, First Ionization Potential, and Density.

If you have trouble with this assignment, you may wait for when we talk a bit more about tables and structures in MATLAB.
