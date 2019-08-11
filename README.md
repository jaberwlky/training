Configure your IntelliJ workspace:  https://www.jetbrains.com/idea/download/#section=windows download the community edition

Download MySQL workbench: https://dev.mysql.com/downloads/workbench/

MySQL Community server: https://dev.mysql.com/downloads/mysql/

Create a personal GitHub workspace for your code.

Create your first application by following this readme. 

clone this project, then do the work, then push up your pull request to the repo. i will look at it then

DATABASE SETUP:
Create a database instance, name it
Create ddl to create a customers table
Import customers.txt to your customers table
Use 'mysqlimport' to create a repeatable script for loading customer data
Requirements

OBJECTIVE:
Create a Java application that will:

Interact with customer records that have been loaded into a database.

Generate an email that provides two lists.  One showing Texas residents, one showing out-of-state residents

Add the ability to read customer information from the database 

Update the customer record with a time-stamp showing when the email was sent

Assume you are writing production-ready code - think long-term maintenance and extensibility

Pay attention to your package and class naming

Comment your code at the right level, and add descriptive Git comments that explain what is included in each commit.

Input:

is in the customers.txt file

Output:

Final listing should send out an email
Listing should show all customer data fields

Sample Output:
=== Texas Customers ===


Customer #2

Lee Kathy

kathy@null.com

3208 Daniel Ave

Dallas, TX 75205-4909


Customer #3

Montague Lucille

lucille@null.com

1609 Menteer Drive

Cedar Park, TX 78613


Customer #4

Sherrie Arturo

arturo@null.com

2024 Lauren Lake Drive

League City, TX 77573


Customer #5

Reed Deborah

deborah@null.com

8610 Southwestern Blvd

Dallas, TX 75206


Customer #6

Logan Trent

trent@null.com

2408 Yorktown

Houston, TX 7705


=== Out of State Customers ===


Customer #1

Kearney Katie

katie@null.com

5122 West 62nd Street

Mission, KS 66205



File format:
Last name
First name
Email address
Home address
City
State
Zip code
Timestamp

Write output to a log file using Log4J
Write errors to an error log using Log4J


