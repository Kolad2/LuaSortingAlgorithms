# Implementation of 20+ sorting algorithms in Lua and Luau

forked from https://github.com/DervexDev/LuaSortingAlgorithms

All algorithms have been ported from Python which can be found on [GeeksforGeeks](https://www.geeksforgeeks.org/sorting-algorithms/) site. Every file is ready to use module which can be imported!

## This repository features following algorithms:

<details>
<summary> Bogo Sort </summary>
Bogo может зависает нахождении в масиве одинаковых элементов.
Это связано с тем,
что алгоритм основывается на случайной перестановке.
</details>

* Bubble Sort
* Bucket Sort
* Circle Sort
* Cocktail Sort
* Comb Sort
* Counting Sort
* Cycle Sort
* Gnome Sort
* Gravity (Bead) Sort
* Heap Sort
* Insertion Sort
* Merge Sort
* Pancake Sort
* Pigeonhole Sort
* Quick Sort
* Radix Sort
* Selection Sort
* ShellSort
* Stooge Sort
* Strand Sort

And all of them in single module named `AllAlgorithms.lua`.

## Limitations:
All of these algorithms are 100% working with **integers** and most of them work with **floats**! *(Bucket, Counting, Gravity, Pigeonhole - these don't work!)*