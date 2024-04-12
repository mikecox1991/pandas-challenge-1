# pandas-challenge-1
First pandas challenge

Part 1
This is my profit sharing data cleaning. I started with understanding what data we were working 
with. df.colums showed us what columns are inside of the program. describe broke downt the data 
showing us different quartiles mean of each column. count() showed up how much data is in each 
column, trying to understand if there was missing data. Item [6] added all the values in the 
category and brought back the categories with the most data, this case consumables was the most
with 23,538. Next was trying to see the most subcategory in category, in this it was bathroom 
supplies. I used loc for this because it access the row of inforamtion I am looking for.
Five Clients was for using value counts and looking at the clinet id and counting how many entries 
they had. The top clients we populated the list by using keys() this takes from the index and
populated the list. From there we added the quantity of the top client and seen how many units
they bought.

Part 2
We created a new column in line [63] "subtotal" that calculates unit price by the product of
quantity. Then we wanted to see the subtotal, unit price, quantity. Next we look at the shipping
I used a function here to look at the weight of unit weight and quantity, see if its more or less 
than 50, depending on that calculate the cost of 7 or 10 dollars and then print the saved variable.
I call that function result using .apply and set the rows with axis=1. The line cost made a new 
column multiplied the unit cost and units then add shipping price, then print the first three on 
the table. Line profit we took the difference from line price and line cost.

Part 3
Good luck!

Part 4
This was the tricky section, I took the .loc method and iterated through top clients and found the 
total of everthing instance of that client in the table and add the line price. The total prints and 
rounded to the second decimal place. Line [88] this was the second hardest compared to Part 3. Here we 
use .loc to get all of our values with the client id instances inside of the table. populate those values
into a dictionary storing the key as the index for the table. After that make a new data frame from those 
values, then sort the values from line profit and descending order. Line[94] was a lot of reps but we renamed
the table into a new data frame. Change the values to the millionths and add the $. Last but not least 
change the order to the most profit first using sort values. 

Pandas is difficult and very brand new to me but I hope you enjoy.



