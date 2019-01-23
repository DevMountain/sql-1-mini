<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250" align="right">

# Project Summary

In this project, we'll be practicing inserting and querying data using SQL. We'll make use of an online database emulator tool found  <a href="https://postgres.devmountain.com/">Here</a>. Careful, if you reload the page your changes will be lost.

On the left are the Tables with their fields. The right is where we will be writing our queries. The bottom is where we will see our results.  

## Step 1

### Instructions

SELECT all the data FROM the artist table.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT * FROM artist;
```

</details>

## Step 2

### Instructions

SELECT the first_name, last_name, and country FROM the employee table.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT first_name, last_name, country
FROM employee;
```

</details>

## Step 3

### Instructions

SELECT the name, composer, and milliseconds FROM the track table WHERE the milliseconds are greater than 299000.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT name, composer, milliseconds
FROM track
WHERE milliseconds > 299000;
```

</details>

## Step 4

### Instructions

SELECT the count FROM the track table WHERE the milliseconds are greater than 299000.

### Solution

<details>

<summary> <code> SQL Solution </code> </summary>

```sql
SELECT count(*)
FROM track
WHERE milliseconds > 299000;
```

</details>

## Black Diamond 

Now that we have some basic query examples.  Let's try doing some more complicated ones.
Use [www.sqlteaching.com](http://www.sqlteaching.com/) or [sqlbolt.com](http://sqlbolt.com/) as resources for the missing keywords you'll need.

1. Find the average length of all tracks in milliseconds
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
<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250">
</p>
