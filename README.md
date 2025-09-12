# Week 2 Assignment: Python List Operations

## Description
This assignment involves performing various operations on a Python list as per the given instructions. The code demonstrates creating a list, appending elements, inserting values, extending with another list, removing elements, sorting, and finding the index of a specific value.

## Instructions
The following operations are performed in the `lists.py` script:
- Create an empty list called `my_list`.
- Append the elements 10, 20, 30, 40 to `my_list`.
- Insert the value 15 at the second position in the list.
- Extend `my_list` with the list [50, 60, 70].
- Remove the last element from `my_list`.
- Sort `my_list` in ascending order.
- Find and print the index of the value 30 in `my_list`.

## How to Run
To run the script, ensure you have Python installed and execute the following command in the terminal:

```
python lists.py
```

## Expected Output
The script will print the state of the list after each major operation and finally output the index of 30.

Example output:
```
After append: [10]
After append: [10, 20]
After append: [10, 20, 30]
After append: [10, 20, 30, 40]
[10, 15, 20, 30, 40]
Extended list: [10, 15, 20, 30, 40, 50, 60, 70]
[10, 15, 20, 30, 40, 50, 60]
[10, 15, 20, 30, 40, 50, 60]
3
```

## Notes
- The code has been corrected based on feedback to use `pop()` for removing the last element and `index()` to find the position of 30.
- This assignment helps in understanding fundamental list manipulations in Python.
