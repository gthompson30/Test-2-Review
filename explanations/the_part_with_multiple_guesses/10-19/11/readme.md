# Question 11
## Question
After this code's run, what will be the value of m?
```java
double x = 5; double y = 2;
int m = (int)(x + y + x / y - x * y - x / (10 * y));
```
a) 0  
b) -1  
c) 1  
d) -0.5  
e) None of these  
## Answer
In Java, the compiler forces the program to obey the PEMDAS system and the operates on same operators from left to right. With this in mind, this is the calculation.
`(int)(5.0 + 2.0)`