# EXPERIMENT 1: INTRODUCTION TO PYTHON PROGRAMMING

This repository contains my Programming Assignment 1 for our Advanced Computer Programming course (S.Y. 2025-2026). It covers three basic Python problems from Module 1.

## Contents

## A. Word Rotation Problem
Goal: Move the first letter of a word to the very end.

How it works:
[1:] gets the whole word except the first letter.
[0] gets only the first letter.
We used + to join them together.

## B. Username Builder Problem
Goal: Make a username from a first and last name. It needs to have small letters, no spaces, and a period in the middle.

How it works:
.lower() makes all the letters small.
.replace(" ", "") removes any spaces.
We used + to connect the names and the period.

## C. Bookend Swap Problem
Goal: Swap the first and last items of a list, but keep the middle items in the same order.

How it works:
first, *middle, last is a fast trick to split the list into three parts.
We used + to put the list back together with the first and last parts swapped.
