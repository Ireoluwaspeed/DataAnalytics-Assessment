# DataAnalytics-Assessment

# Solution to the Questions
# Question 1.
I check the all the tables and have a little understand of about the tables, then I combine the first name and last name together, then counted users plans with their type of savings plan column (is_regular_savings and is_fixed_invesment) and also join Plans_plan and user_customuser tables together with the foreign keys also doing a check with a where clause of is_funging must be 1 later grouping them with their user customuser id also using a case function to check if the amount is greater than zero.

# Question 2.
I counted all customer in 'user_customuer' table and find the average of “avg_txn_per_month” and Timestamdiff and cutdate function to find the different between the in value and using case function to categorize the result into different grades is requested later joining “savings_savingsaccount” and “users_customuser” and grouping by frequence and frequency categories field.

# Question 3.
I find the last seen date and also calculate the date difference from the current date with Datediff function and checking with having clause if the last seen date or last transaction date is greater than 365 days.

# Question 4.
I calculated tenure in months using timestampdiff and also calculated total transactions and I also estimated customer life time value using round function to do some calculation also joining users_customuser and savings_savingsaccount tables after grouping by Id and ordering properly.




#My Challenges:
•	I had challenge with the version of my workbench. I have to uninstall and reinstall and newer version before it can work properly 
•	All the data base I’m currently working is clone to a Retool library because of network I address changes some functions am used to did not work properly on workbench, it took a lot of time to be use some function properly after reading a little on how it can be manipulated in my workbench or other function that can perform the same task.
•	Understanding of all the dataset in each of the table to be able to answer the question in a short time

