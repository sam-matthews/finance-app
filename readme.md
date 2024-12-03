# Readme

This is my finance app.

## Initially

Initially I will work through various component, learn how each component works, then get an understanding on how each component will integrate with each other and then write some specific code relating to my finance app.

## What are the components

GUI interface, we will start with tkinter and look to progress with other packages.

### Classes

Learn how classes work and how they can be used to make the code more efficient.

### Install postgres database

Install database and write some code which will run some functions to do things in the database.

- DDL
- DML
- Batch jobs

### Integrate UI with Database commands

- Create a button which will run some code, which in turn runs some code in the database. For examaple to run DDL.
- Create a view which will list some data, extent this out to a table view to look at lots of data.

### Stock Data API

Implement some code to download latest stock data, make it based on specific stocks, so we don;t download everything. Just the stocks I am currently looking at.

Use the requests package to store in a dictionary, then insert that into a database and then implement that data into a list view.

### Implement menu system in UI

Implement a menu system so we can run commands via the menu. For example create a page which deals with running DDL and another menu item and page which will enable the user to view the data.

### Stock Batch

Generate some code which creates additional views or tables in the database. For example, generate some reports which reports on monthly data, then pop that into a table view in the database.
