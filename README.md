# EXPERIMENT 1: INTRODUCTION TO PYTHON PROGRAMMING

This repository contains my Programming Assignment 1 for our Advanced Computer Programming course (S.Y. 2025-2026). It covers three basic Python problems from Module 1.

## Objective

The objective of this activity is to apply basic Python programming concepts through string manipulation, string methods, slicing, functions, and sequence unpacking.

## Detailed Discussion of the Experiment

This activity was completed using Python in a Jupyter Notebook. It consists of three programming problems: Word Rotation, Username Builder, and Bookend Swap.

### A. Word Rotation Problem

For the Word Rotation Problem, I used string slicing to move the first character of the string to the end.

I used "She Will" as my example.

The code was:

rotate_word_1 = "She Will"
print(rotate_word_1[1:] + rotate_word_1[0])

The output was:

he WillS

The [1:] gets all the characters starting from the second character, while [0] gets the first character. The two parts are then joined together using +.

### B. Username Builder Problem

For the Username Builder Problem, I created a function called make_username().

The function converts the first and last names to lowercase and removes spaces using the replace() method. It then joins the two names using a period.

I tested the function using my name:

make_username("Jairus", "Ramos")

The output was:

jairus.ramos

### C. Bookend Swap Problem

For the Bookend Swap Problem, I created a function called swap_bookends().

The function uses sequence unpacking to separate the first element, middle elements, and last element of a list.

The sequence unpacking used was:

first, *middle, last = items

The first and last elements are then exchanged while the middle elements remain in their original order.

I tested the function using three different lists.

The outputs were:

[7, 2, 3, 4, 5, 6, 1]

["blue", "green", "red"] 

[3, 8]
