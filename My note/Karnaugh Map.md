### Karnaugh Map

#### Way 1: Minterm:

> 1. Found the linked Minterm(**find the "stable" element**), then combine them with the **OR**
> 2. You can also combine the nodes in the different boundary.
>
> ![1540263014307](C:\Users\29551\Documents\2018Autumn\Digital design\lecture_notes\picture\1540263014307.png)
>
> 
>
> **Result:  y | (~w & ~z  & y) | (x & ~z  & y)**



#### Way 2 :  Maxterm: 

> 1. Find the Maxterm, Do the same thing as the Way 1
> 2. However, when represent the equation, use the inverse  of the element and combine block them with the "|" and the final result is the product of these maxterms.
>
> ![1540264929239](C:\Users\29551\AppData\Local\Temp\1540264929239.png)
>
> **Result: (~C | ~ D) & (D | ~B) & ( ~A | ~ B )**