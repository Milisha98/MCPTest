Latest Epicor Changes

## Project Structure:
1) ASP.Net 8 minimal Web-API that connects to the database.
2) A Javascript front-end that reads from the Web-API.

## Technologies used:
    - Web-API:
        - SQL Server
        - ASP.Net 8
        - C#
    - Front End:
        - Tailwind CSS
        - DaisyJS
        - Javascript
        - HTML


## Overview:

Step 1:

Create a ASP.Net 8 Minimal API which returns the 5 latest changes to the `[Erp].[Customer]` table returning:
 - CustomerID (`CustID`)
 - Name
 - Last Updated By (`ChangedBy`)
 - Last Updated Date (`ChangeDate`)

The sort order will be `ChangeDate` and `ChangeTime`, both in descending order.


Step 2:

Create a HTML page that uses Tailwind CSS and DaisyJS.
It must consume the API in Step 1.

Please present the results in a table format.


## Project Structure

Keep a **flat and predicatable** folder structure

