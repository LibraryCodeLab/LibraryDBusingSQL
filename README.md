<h1>Project: Library Database</h1>

In this exercise, we will download an existing database that includes a list of library books and library users. 

1. Download the Library.db from the <a href="https://github.com/LibraryCodeLab">Codelab Github</a>.  

2. Go to <a href="www.sqlliteonline.com>sqlliteonline.com</a> and select File > Open DB and choose the Library.db file. 

3. First, use your SELECT command to see what is in the database. 

<b>SELECT</b> * <b>FROM</b> Books; 

4. Use the WHERE command to filter based on a condition: 

<b>SELECT</b> * <b>FROM</b> Books <b>WHERE</b> Collection=”gna”; 

5. Add a new user to your Users database (leave Book field blank). 

Add two new books. 

6. “Check out” one of the new books to one of your users. 

7. Pull a list to show what books are checked out to which users. 

*Can you edit this list to only show the book title and user first * last name? 

8. Create a new table that lists 3 library locations and shows which books are at those locations. 

9. Pull a list of which books are at which locations. 

<h2>BONUS</h2> 

Create your own database. You might want to sketch out what tables and fields you want. You can delete the library tables using DROP TABLE or you can just add some new tables in the existing Database.
