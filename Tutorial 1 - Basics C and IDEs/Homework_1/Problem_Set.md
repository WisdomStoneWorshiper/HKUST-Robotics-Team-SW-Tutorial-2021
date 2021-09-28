# Homework for Tutorial 1 - Basics of C [![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](https://hackmd.io/@Oil/H1nE_uU7t)
#### Total Score: 

Author: Li Ka Yau Elwin

## Table of Content

[TOC]

## Absolute Grading

MATH 1012 and MATH 1013 are harsh. They are graded by your total scores among your homework, mid-term exam and final exam, instead of graded by comparing your total scores to others.

Following is the score-to-grade table of the two courses:

| Score Range |  Grade  |
|:-----------:|:-------:|
|  85 - 100   | A Range |
|   75 - 84   | B Range |
|   55 - 64   | C Range |
|   35 - 44   | D Range |
|   25 - 34   | E Range |
|   0 - 24    | F Range |

Write a program, when TAs input your total scores to the program, the program output the corresponding range of your grade.

For example:

Input:
`89`

Output:
`A Range`

> :exclamation: No need to handle non-numerical inputs such as "abc" and "ilovetimwoo")

Skeleton Code is provided: [Skeleton Code for "Absolute Grading"](https://github.com/HKUST-Robotics-Team/Software-Tutorial-2021/blob/master/Tutorial%201%20-%20Basics%20C%20and%20IDEs/Homework_1/Skeleton_Code/Absolute_Grading/main.c)

## Tic-Tac-Toe

Have you ever played tic-tac-toe before? It is a simple game for two players, who take turns marking spaces in a 3 X 3 grid. The player who succeeds in placing three of their marks in a diagonal, horizontal, or vertical row is the winner.

You can try this out at: https://playtictactoe.org/

Write a program which two players (PVP) can play this game together.
> :exclamation: No need to handle non-numerical inputs such as "abc" and "ilovetimwoo")

Skeleton code is provided: [Skeleton Code for "Tic-Tac-Toe"](https://github.com/HKUST-Robotics-Team/Software-Tutorial-2021/tree/master/Tutorial%201%20-%20Basics%20C%20and%20IDEs/Homework_1/Skeleton_Code/Tic-Tac_Toe)

Tips: Using Array and Switch Statement are highly recommanded.

### Bonus

Write a program which only one player can be played with the computer as his / her foe (PVE).

## Simple Calculator

A simple calculator can only do simple mathematical operations (i.e. Addition, Subtraction, Multiplication and Division.)

Write a program of a Simple Calculator with input format for users:
`<number><operator><number>`
with spaces are unnecessary in between.

For example:

Input:
`2`
`+`
`3`

Output:
`5`

Input:
`1`
`-`
`3`

Output:
`-2`

Input:
`3`
`*`
`4`

Output:
`12`

Input:
`9`
`/`
`2`

Output:
`4.5`

Tips: Using Switch Statement is highly recommanded.

Skeleton Code is provided: [Skeleton Code for "Simple Calculator"](https://github.com/HKUST-Robotics-Team/Software-Tutorial-2021/tree/master/Tutorial%201%20-%20Basics%20C%20and%20IDEs/Homework_1/Skeleton_Code/Simple_Calculator)

## Challenging Question - Score Attack

Let say a string is given to you which only involve 'A', 'B' and 'C'. E.g. 'AACCBBCCCAAA'.

What you need to do, is to write a program to eliminate the linking letters. Everytime you eliminated a letter, one mark will be given. For example, if we eliminated the 'BB' in the above example, 2 marks will be given. 

However, scores can be multiplicated when you can eliminate 5 or above letters in a row. For instances, after eliminating 'BB', the remaining string will become 'AACCCCCAAA'. So if we eliminate 'CCCCC', 5 x 1.5 = 7.5 scores will be given. The table of multiplication is shown below:

| Letters Eliminated | Multiplication |
| ------------------ | -------------- |
| 5                  | 1.5            |
| 6                  | 1.6            |
| 7                  | 1.7            |
| 8                  | 1.8            |
| 9                  | 1.9            |
| 10                 | 2.0            |
| 11                 | 2.1            |
| 12                 | 2.2            |
| 13                 | 2.3            |
| 14                 | 2.4            |
| 15                 | 2.5            |
| 16                 | 2.6            |
| 17                 | 2.7            |
| 18                 | 2.8            |
| 19                 | 2.9            |
| 20                 | 3.0            |
| 21                 | 3.1            |
| 22                 | 3.2            |
| 23                 | 3.3            |
| 24                 | 3.4            |
| 25                 | 3.5            |
| 26                 | 3.6            |
| 27                 | 3.7            |
| 28                 | 3.8            |
| 29                 | 3.9            |
| 30                 | 4.0            |

Write a program to eliminate all the letters, in addition to get the highest score you can get.

No skeleton code is given for this question. Write your own program and add oil (literally me cuz my name is Oil Rabbit) UwU.
