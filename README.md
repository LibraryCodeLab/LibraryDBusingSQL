<h1>Project: Library Database</h1>

In this exercise, we will download an existing database that includes a list of library books and library users. 

Download the Library.db from the Codelab Github (github.com/library codelab).  

Go to sqlliteonline.com and select File > Open DB and choose the Library.db file. 

First, use your SELECT command to see what is in the database. 

SELECT * FROM Books; 

Use the WHERE command to filter based on a condition: 

SELECT * FROM Books WHERE Collection=”gna”; 

Add a new user to your Users database (leave Book field blank). 

Add two new books. 

“Check out” one of the new books to one of your users. 

Pull a list to show what books are checked out to which users. 

*Can you edit this list to only show the book title and user first * last name? 

Create a new table that lists 3 library locations and shows which books are at those locations. 

Pull a list of which books are at which locations. 

BONUS 

Create your own database. You might want to sketch out what tables and fields you want. You can delete the library tables using DROP TABLE or you can just add some new tables in the existing Database.
