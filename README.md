![GitHub Logo](https://s3.ap-south-1.amazonaws.com/greyatom-social/GreyAtom-logo.png)

# Distinct Keyword

The SQL DISTINCT keyword is used in conjunction with the SELECT statement to eliminate all the duplicate records and fetching only unique records.

There may be a situation when you have multiple duplicate records in a table. While fetching such records, it makes more sense to fetch only those unique records instead of fetching duplicate records.

### Syntax

The basic syntax of DISTINCT keyword to eliminate the duplicate records is as follows −

        SELECT DISTINCT column1, column2,.....columnN
        FROM table_name
        WHERE [condition]

### Example

Lets find out all Cities present in Customers table.

        Select City from Customers;

Above example will list all cities with duplicate values. Add distinct keyword to remove duplicates.

        Select distinct City from Customers;
