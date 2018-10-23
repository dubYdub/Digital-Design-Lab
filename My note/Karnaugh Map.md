### Karnaugh Map

#### Way 1: Minterm:

> 1. Found the linked Minterm(**find the "stable" element**), then combine them with the **OR**
> 2. You can also combine the nodes in the different boundary.
>
> ![Capture2](C:\Users\29551\Documents\2018Autumn\Digital design\Digital-Design-Lab\Pictures\Capture2.JPG)
>
> 
>
> **Result:  y | (~w & ~z  & y) | (x & ~z  & y)**





#### Way 2 :  Maxterm: 

> 1. Find the Maxterm, Do the same thing as the Way 1
> 2. However, when represent the equation, use the inverse  of the element and combine block them with the "|" and the final result is the product of these maxterms.
>
> ![Capture](C:\Users\29551\Documents\2018Autumn\Digital design\Digital-Design-Lab\Pictures\Capture.JPG)
>
> **Result: (~C | ~ D) & (D | ~B) & ( ~A | ~ B )**





#### More complex Karnaugh Map

> ##### *5-attributes : two 4-attributes maps*
>
> ![Capture3](C:\Users\29551\Documents\2018Autumn\Digital design\Digital-Design-Lab\Pictures\Capture3.JPG)
>
> ##### *6-attributes or more : More 4-attributes maps*
>
> ![Capture4](C:\Users\29551\Documents\2018Autumn\Digital design\Digital-Design-Lab\Pictures\Capture4.JPG)

