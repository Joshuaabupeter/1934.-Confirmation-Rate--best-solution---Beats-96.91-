# 1934.-Confirmation-Rate--best-solution---Beats-96.91-

MY approach to solving the problem
1. Create 2 columns. 1. to count confirmations and 2. to count timeouts
2. sum up the columns to get the to confirms and total timeouts and group by user_id
3. Now divide the total confirmations for each user by the sum of the confirmations and timeouts. Do not forget to group by user_id 
