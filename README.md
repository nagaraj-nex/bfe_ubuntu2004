# bfe

_sample_

```python
>>> supported_platforms = ['nexus', 'catalyst']
>>>
>>> for platform in platforms:
...     if platform in supported_platforms:
...         print("Platform {}  -- SUPPORTED".format(platform))
...
...
Platform nexus  -- SUPPORTED
Platform catalyst  -- SUPPORTED
>>>
```
***test***

ALWAYS, if a dictionary key may not exist, do NOT use the notation like `dict['key']`.  Instead, you should use `dict.get('key')`

'''java
import java.util.Scanner;

public class FibonacciSeries {

public static void main(String[] args) {

int num, a = 0,b=0, c =1;

Scanner in = new Scanner(System.in);

System.out.println("Enter the number");

num = in.nextInt();

System.out.println("Fibonacci Series of the number is:");

for (int i=0; i<num; i++) {

a = b;

b = c;

c = a+b;

System.out.print(a + "");

}

}

}
'''
