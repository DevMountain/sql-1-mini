<img src="https://devmounta.in/img/logowhiteblue.png" width="250" align="right">

# Project Summary

In this project, we'll be practicing inserting and querying data using SQL. We'll make use of this online tool called <a href="http://jxs.me/chinook-web/">Chinook</a>.

On the left are the Tables with their fields. The right is where we will be writing our queries. The bottom is where we will see our results.  

## Step 1

### Instructions

SELECT all the data from the Artist table.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT * FROM Artist;
```

</details>

## Step 2

### Instructions

SELECT the FirstName, LastName, and Country from the Employee table.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT FirstName, LastName, Country
FROM Employee;
```

</details>

## Step 3

### Instructions

SELECT the Name, Composer, and Milliseconds FROM the Track table WHERE the Milliseconds are greator than 299000.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT Name, Composer, Milliseconds
FROM Track
WHERE Milliseconds > 299000;
```

</details>

## Step 4

### Instructions

SELECT the count FROM the Track table WHERE the Milliseconds are greator than 299000.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT count(*)
FROM Track
WHERE Milliseconds > 299000;
```

</details>

## Black Diamond 

Now that we have some basic query examples.  Let's try doing some more complicated ones.
Use [www.sqlteaching.com](http://www.sqlteaching.com/) or [sqlbolt.com](http://sqlbolt.com/) as resources for the missing keywords you'll need.

1. Find the average length of all tracks in Milliseconds
2. Find the number of invoices in the USA
3. Make a list of all the First Names of Customers that contain an 'a'
4. Make a list of the 10 longest tracks
5. Make a list of the 20 shortest tracks
6. Find all the customers that live in California or Washington
7. Find all the customers that live in California, Washington, Utah, Florida, or Arizona (Use IN keyword)
8. Insert an artist to the database
9. Insert yourself as a customer to the database
10. Find a list of all Playlists that start with `Classical` 
11. You can either continue exploring this dataset or look into setting up postgres on your local machine.

## Contributions

If you see a problem or a typo, please fork, make the necessary changes, and create a pull request so we can review your changes and merge them into the master repo and branch.

## Copyright

© DevMountain LLC, 2017. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.

<p align="center">
<img src="https://devmounta.in/img/logowhiteblue.png" width="250">
</p>
