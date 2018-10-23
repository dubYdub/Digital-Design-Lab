## Lecture1



### 1.number base conversion

 *If the number includes a radix point, it is necessary to separate the number into an integer part and a fraction part, since each part must be converted differently*

**for the integer part:**

![1536762480664](C:\Users\29551\AppData\Local\Temp\1536762480664.png)

**for the fraction part:**

![1536762508148](C:\Users\29551\AppData\Local\Temp\1536762508148.png)

### 2.complements  of numbers

> *used to simplify the subtraction operation*
>
> ***Radix Complement  = Diminished Radix Complement + 1***
>
> The complement of a complement leads to its origin value

##### 1.Diminished Radix Complement 

$$
(n^{x} - 1)-N
$$

​						(n is digit, x is the length of N)



##### 2.Radix Complement 

$$
n^{x} -N
$$

​						(n is digit, x is the length of N)



##### 3.Use complement to simplify subtraction

> 1.Add the minuend M to the r’s complement of the subtrahend N. Mathematically, **M + (n^x - N) = M - N + n^x.**       
>
> 2.If  M > N, the sum will be :  **M + (n^x - N)  - n^x**
>
> 3.If  M < N,    the sum does not produce an end carry and is equal to    r^n - (N - M),    which is the r’s complement of    (N - M).    To obtain the answer in a familiar form, take the r’s complement of the sum and place a negative sign in front.   

### 3.Signed number

*the minus of a number is just the radix implement of it*

##### 1.Addition

> Just add them.
>
> A carry out of the sign‐bit position is discarded.
>
> If the value of a addition has to be represented by one more  bit, it will cause **overflow**

##### 2.Subtraction

