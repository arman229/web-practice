# CSS Selectors
## Simple Selectors

- ### Id selector

    Id selectors select a single html element by his id.
    id selectors are accessed by applying # at start of the id of element
    for p has id of **para** and style can be applied using

      #para {
       color:red;
      }

- Class Selector

   class selector apply the style to all elements of same class
   for example some elements has class **red-button**
 
      .red-button{
        color:red;
       }
## css comments 

   Comments are the pieces of information that are not
executed in computer when the program runs, also it is 
very helpful for future and other programmer.
in css comments starts with /* and end with */.

  ## Css colors 
Css colors can be applied by using three different 
ways.
- ### 1 rgb(red, green, blue)
- ### 2 hex(#rrggbb)
- ### 3 hsl(hue, saturation lightness )
note that: the value of red, green and blue varies from 
0 to 255 in hsl we convert these values in hexadecimal
(divided by 16 so, the remainder is always in between 0 to 15 when remainder
is 10 we replace it by a , when remainder is 11 we replace it by b and 
continue this process upto  15 which is equal to f)
 