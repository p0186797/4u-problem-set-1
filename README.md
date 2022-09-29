# 4u-problem-set-1

Create a java file called **ActualProblemSet.java** and upload it to this repo. For each program, do not have any extraneous print statements i.e. no prompts. The output must be exact.

---

Inside that file create a class called **TrueAndFalseQuestion**.

Write a program that reads 2 lines from the user. Both lines represent a sequence of T and F that will be the same length. The first line represent's a student's answers for a test. The second line represents the actual answers. Your program outputs the number of correct answers.

For example:

TFTTT and FTTFT

TFTTT is the student's. FTTFT is the actual answer key. This student got 2 answers correct.

&nbsp;&nbsp; **Sample Input 1**

    TFTTT
    FTTFT

&nbsp;&nbsp; **Sample Output 1**

    2


&nbsp;&nbsp; **Sample Input 2**

    TFTTTTFFFFFT
    FTTFTFTFTFTF

&nbsp;&nbsp; **Sample Output 2**

    4
    
---

Inside that file create a class called **MaxAndMinQuestion**.

Write a program that reads a sequence of grades (0 - 100) from the user until the user enters QUIT. Your program outputs the max and min grade.

&nbsp;&nbsp; **Sample Input 1**

    50
    45
    90
    100
    QUIT

&nbsp;&nbsp; **Sample Output 1**

    100
    45

---

Inside that file create a class called **MagicSquareQuestion**.

Write a program that reads 3 lines from the user. Each line will consisted of 3 single digit numbers separated with a space (1 2 3).
Your program outputs if the three lines make a magic square.

1. A magic square has 1 occurence of each digit from 1 to 9.

2. The sum of each row is the same.

(There are more conditions but we will ignore them.)

For example:

2 7 6
9 5 1
4 3 8

Represents a magic square because it uses all 9 digits and each row sums to 15.

&nbsp;&nbsp; **Sample Input 1**

    2 7 6
    9 5 1
    4 3 8

&nbsp;&nbsp; **Sample Output 1**

    yes

&nbsp;&nbsp; **Sample Input 2**

    2 5 7
    4 6 8
    9 3 1

&nbsp;&nbsp; **Sample Output 2**

    no
