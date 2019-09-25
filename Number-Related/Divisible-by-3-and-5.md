
## 2.4: Divisible by 3 and 5

**S-1: The problem**
For a given number, find all the numbers smaller than the number. Numbers should be divisible by 3 and also by 5.

<details>
 <summary><b>S-2: Click Here For Show Hints</b></summary>
   <p>So, you have to check two conditions: make sure the number is divisible by 3, and also by 5.

> Hence, you will need to use two conditions.
</p>
 </details>
<br>

**[Try It:](/https://play.google.com/store/apps/details?id=com.learnprogramming.codecamp)**

#### S-3: Solution
```python
def divisible_by_3and5(num):
   result = [ ]
   for i in range(num):
       if i%3 == 0 and i%5 == 0:
           result.append(i)
   return result
 
num = int (input('Enter your number: '))
result = divisible_by_3and5(num)
print(result)
```

**[Try It:](/https://play.google.com/store/apps/details?id=com.learnprogramming.codecamp)**

#### S-4: Explanation
This one is easy. We took an input number from the user, and then pass it to a function. 

In the function, we have a list and we ran a loop. This loop runs a range. This means we will get numbers from 0 to num. Here, num is the number that the user entered. 

Inside the loop, we have an if block. In the if block, we have two conditions. One condition says i % 3 ==0

This means if you divide i by 3 and there will not be any remainder. If there is no remainder then the number is divisible by 3. 

Similarly, i%5==0 means the number is divisible by 5.

As we have and between both conditions, to go, insider, the if-block, the i has to be divisible by 3 and also has to be divisible by 5. 

Inside the if block, we are appending the number in the result list. And then return the list. 

That’s how we are getting every number divisible by 3  and 5. 

> Isn’t it simple and cool?

#### S-5: Quiz
If you want to get the numbers that are either divisible by 3 or divisible by 7, which condition will you use?

1. n%3 == 0 or n%7 ==0
2. n%3 == 0 and n%7 ==0
3. n%3 == 0 || n%7 ==0

**The answer is: 1**

#### S-6: Take Away
Remainder(%) will be 0, if the number gets divided.

&nbsp;
[![Next Page](../assets/next-button.png)](Sum-of-digits.md)
&nbsp;

###### tags: `programmig-hero` `python` `float` `int` `math` 