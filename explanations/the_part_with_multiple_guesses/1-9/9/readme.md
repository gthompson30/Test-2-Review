# Question 9
## Question
What is the result of running this code?
(code was edited to make it runnable)
```java
class recursion
{
	int func (int n)
	{
		int result;
		result = func(n - 1);
		return result;
	}
}

public class Output {
	public static void main(String[] args)
	{
		recursion obj = new recursion();
		System.out.println(obj.func(12));
	}
}
```
a) 0  
b) 1  
c) -1  
d) compile-time error  
e) runtime error
## Answer
Look at the `func` method in the `recursion` class. The function seems to take in `n`, but doesn't do anything with it. Therefore, the function keeps calling itself without any way to stop. This causes the lovely `java.lang.StackOverflowError` error.

This is a runtime error as the compiler lets the code compile.

### **The answer is e).**