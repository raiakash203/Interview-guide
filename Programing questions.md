## Questions:

1. Write a python function that accepts a string s, reverse the string according to the following rules:

* All the characters that are not English letters remain in the same position.
* All the English letters (lowercase or uppercase) should be reversed.
Return s after reversing it.

Input: s = "ab-cd!"
Output: "dc-ba!"

2.Write a SQL query to find all the products which only have critical accessories.
product   accessory        critical(1,0)
P1        Headphone         1
P2        Pendrive          1
P1        Neckband          0
P3        Airpods           0
P4        Mic               1
P4        Speaker           1

3. What is the output of the below

  Table A  Table B
   ID  ID
   1  1
   1  1  
   1



What will be the output of the following queries:
 1.Select count(*) from A inner join B on A.ID =B.ID 
 2.Select count(*) from A left join B on A.ID =B.ID 
 3.Select count(*) from A left anti  join B on A.ID =B.ID
 4.Select count(*) from A right   join B on A.ID =B.ID 
 5.Select count(*) from A right   join B on 1=2 



4. You are given a dictionary with a key-value of {string: number} where values in the dictionary could be duplicates. You are required to extract the unique values from the dictionary where the value occurred only once.
Return a list of values where they occur only once.
Note: You can return the values in any order.
Input:
dictionary = {"key1": 1, "key2": 1, "key3": 7, "key4": 3, "key5": 4, "key6": 7}
Output:
find_unique_values(dictionary) -> [3,4]


5. Given the transactions table below, write a query that finds the third purchase of every user.
Note: Sort the results by the user_id in ascending order. If a user purchases two products at the same time, the lower id field is used to determine which is the first purchase.

Example:
Input:
transactions table
id			int
user_id		int
created_at		datetime
product_id		int
quantity		int


Output:
user_id
created_at
product_id
quantity
