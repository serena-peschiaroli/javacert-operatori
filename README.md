- 1

int a = 3;

a = ++a + ++a;

a = -- a - -- a;

System.out.println(a);

a


- 2. 
What is the output of the following code?


public class Foo {

  public static void main(String[] args) {

    int a = 10;

    long b = 20;

    short c = 30;

    System.out.println(++a + b++ * c);

  }

}

The are 1 correct answers

[x]611
930
960
641

- 3. 

Given the code fragment:


System.out.println(10 == 10 && ! (5 != 5));

System.out.println(10 < 8 || 10 > 2);


What is the result?

The are 1 correct answers

[x]TRUE TRUE
TRUE FALSE
FALSE FALSE
FALSE TRUE





- 4. 

What output is to be expected from the code provided?
The are 1 correct answers

package com.company;
public class Main {

public static void main(String[] args) {

int marksGot = 23;
int totalMarks = 100;
int result = (marksGot/totalMarks > 0) ? marksGot -- - 10: (++marksGot/3)*2;
System.out.print(result);

}

}

24
6
1
[x]16
Zero
12

- 5. 

Identify two valid data types for the operands of the addition (+) operator?

The are 2 correct answers

[x]string
boolean
[x]numeric
array


- 6. 

Consider the following program and predict the output:


class Test {

  public static void main(String[] args) {

    String s = new String(“5“);

    System.out.println(1+10+s+1+10);

  }

}

The are 1 correct answers

11511
[x]115110
27
1105110


- 7. 

What is the output of the following Java program?
The are 1 correct answers

public class Main {

public static void main(String[] args) {

int arr[] = {5, 65, 47, 99, 84, 32, 94, 12, 40, 76};

for (int i : arr) {
if(++i < 100){
System.out.print(i + " ");

}

}
}
}

5 66 48 85 33 13 41 77
77 41 13 95 33 85 48 66 6
76 40 12 94 32 84 47 65 5
6 66 48 85 100 33 95 13 41 77
[x]6 66 48 85 33 95 13 41 77
5 65 47 84 32 94 12 40 76

- 8. 

Fill in the blanks: The operators!=, _______, _______, _______,

and++are listed in the same or increasing level of operator precedence.

(Choose two.)

The are 2 correct answers

[x]==,*,!
[x]/,%,*
*,??,/
!,*,%
+=,&&,*
*,<,/


- 9. 

What is the output of the following code?
The are 1 correct answers
package com.company;

public class Main {
public static void main(String[] args) {
int abc = 10;
System.out.println(abc -- + -- abc * abc);

}
}

90
100
95
110
[x]74
50

- 10. 

Given the code fragment:


System.out.println(“Result: “ + 3 + 5);

System.out.println(“Result: “ + (3 + 5));


What is the result?

The are 1 correct answers

Result: 8, Result: 35
Result: 8, Result: 8
- [x] Result: 35, Result: 8
Result: 35, Result: 35

- 11.  

Which of the following is an invalid operator in Java?
The are 1 correct answers

<< 
%
&&
[x]!==
||
>=

- 12. 

Given the following code:


int i1 = 1, i2 = 2, i3 = 3;

int i4 = i1 + (i2 = i3);

System.out.println(i4);


What is the result?

The are 1 correct answers

Compilation fails on line 2
3
Compilation fails on line 1
[x]4

- 13. 

In Java , the single equals operator is used to compare two variables and the double equals operator is used to assign values to a variable.
Is this statement Correct or Incorrect?

The are 1 correct answers

Correct
[x]Incorrect

- 14. 

Given the code fragment:
int a = 3;

a = ++a + ++a;

a = -- a - -- a;

System.out.println(a);

 

What is the output?

The are 1 correct answers
8
3
- [x] 0


- 15. 
Select a code snippet from the following which will generate variable a value as 9 and variable b value as 8.
The are 1 correct answers

A. int a = 1
b = a --;

B. int a = 10, b = 10;
b = -- a;
b++;

C. int a = 10, b = 10;
b --; a++;
a = b --;

Only B
- [x] Only C
Both A and B
Both A and C
Only A
Both A and B


- 16. 

What will the following code print when run?


public class Pass2 {

 public static void main(String[] args) {

  int x;

  int y;

  System.out.print(” main x = ” + x++);

  System.out.print(” main y = ” + ++y);

 }

}

The are 1 correct answers

- [x]Compilation fails
main x = 1 main y = 1
main x = 1 main y = 0
An exception is thrown at runtime
main x = 0 main y = 0
main x = 0 main y = 1


- 17. 

Given the code fragment:


int a = 10;

int b = 20;

int c = 30;

System.out.println(a++ > 10 || ++b <= 21);

System.out.println(a > 10 && ++b <= 22);

System.out.println(a <= 11 && b == 22);

System.out.println(c++ == 31 && a++ == 11 || b++ == 22);


What is the result?

The are 1 correct answers

FALSE FALSE FALSE FALSE
TRUE FALSE FALSE FALSE
- [x] TRUE TRUE TRUE TRUE
TRUE TRUE TRUE FALSE

- 18. 

Project the output of the code snippet.
The are 1 correct answers

package com.company;

public class Main {

public static void main(String[] args){
int a = 5, b=6;
System.out.print(a++ == -- b && b/2 == a-2);

}
}

false false
TRUE
true false
false tru
true true
- [x]FALSE

- 19. 
Given the following code fragment:

 

public static void main(String[] args) {

int a = 10, b = 15;

boolean result = false;

// line n1

System.out.println(result);

}

 

Which two statements, when inserted at line n1 independently, enable the code to print true?

The are 2 correct answers
- result = a > b;
result = ( a !> b );
[x] result = !( a > b);
result = a == b;
-[x]result = a != b;