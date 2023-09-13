# Array
An array is a collection of items stored at contiguous memory locations. The idea is to store multiple items of the same type together. This makes it easier to calculate the position of each element by simply adding an offset to a base value.
## Basic Terminology
- **Array Index**: In an array, elements are identified by their indexes. Array index starts at 0.
- **Array Element**: Elements are items stored in an array and can be accessed by their index.
- **Array Length**: The length of an array is determined by the number of elements it can contain
  
## Representation of Array
The representation of an array can be defined byt its declaration. A declaration means allocating memory for an array of a given size. 
![Alt txt](https://media.geeksforgeeks.org/wp-content/uploads/20220721080308/array.png "Array")
```
# Python Code Example
arr = [10, 20, 30]
```
```
// C# Code Example
int[] arr = new int[5];
```
![Alt txt](https://media.geeksforgeeks.org/wp-content/uploads/20220721113333/Arraydeclaration-660x168.png "Array Declaration")
The above declaration is a **static** or **compile-time** memory allocation, which means that the array element's memory is allocated when a program is compiled. Here only a fixed size of memory will be allocated for storage, but don't you think it will not be the same situation as we know the size of the array every time, but there might be a case where we don't know the size of the array. If we declare a larger size and store a lesser number of elements will result in a wastage of memory or either be a case where we declare a lesser size then we won't get enough memory to store the rest of the elements. In such cases, static memory allocation is not preferred. 

**Dynamic memory allocation** is the process of assigning the memory space during the execution time or the run time. 
```
# C# Code Example
int[] numArray = new int[] {};
```

## Why Array Data Structures are used
If we were to have a large number of variable tracking records, if the number of factors becomes very large it would be challenging to manipulate and maintain the data. **The idea of an array is to represnet many instances in one variable.**
![Alt txt](https://media.geeksforgeeks.org/wp-content/uploads/20220728175153/Needforarray-660x379.png "Array Use Case")

## Types of arrays:
There are majorly two types of arrays:
- **One-dimensional array (1-D array)**: You can imagine a 1d array as a row, where elements are stored one after another.
![Alt txt](https://media.geeksforgeeks.org/wp-content/uploads/20220721112600/1Darray.png "1-D Arrays")
- **Two-dimensional array**: 2-D Multidemnsional arrays can be considered as an array of arrays or as a matrix consisting of rows and columns.
![Alt txt](https://media.geeksforgeeks.org/wp-content/uploads/20220721112715/2Darray.png "2-D Arrays")
- **Three-dimensional array**: 3-D Multidemensional array contains three dimensions, so it can be considered an array of two-dimensional arrays.
![Alt txt](https://media.geeksforgeeks.org/wp-content/uploads/20230321164742/3D-array.png "3-D Arrays")

## Types of Array Operations:
- Traversal: Traverse through the elements of an array.
- Insertion: Inserting a new element in an array.
- Deletion: Deleting element from the array.
- Searching: Search for an element in the array.
- Sorting: Maintaing the order of elements in the array

## Advantages of using Arrays:
- Arrays allow random access to elements. This makes accessing elements by position faster.
- 
