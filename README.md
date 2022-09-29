<h1>Project: Library Database</h1>

In this exercise, we will download an existing database that includes a list of library books and library users. 

1. Download the <a href="https://github.com/LibraryCodeLab/LibraryDBusingSQL/blob/master/LibraryData.db">LibraryData.db</a> from the <a href="https://github.com/LibraryCodeLab">Codelab Github</a>.  

2. Go to <a href="https://sqliteonline.com/">sqliteonline.com</a> and select File > Open DB and choose the <a href="https://github.com/LibraryCodeLab/LibraryDBusingSQL/blob/master/LibraryDatabase2022.db">LibraryDatabase2022.db</a> file. 

3. First, use your SELECT command to see what is in the database. 

         SELECT * FROM Books; 

4. Use the WHERE command to filter based on a condition: 

         SELECT * FROM Books WHERE Collection="gna"; 

5. Add a new user to your Users database (leave Book field blank). 

6. Add two new books. 

7. “Check out” one of the new books to one of your users. 

8. Pull a list to show what books are checked out to which users. 

9. Can you edit this list to only show the book title and user first * last name? 

<h2>Bonus</h2> Create a new table that lists 3 library locations and shows which books are at those locations. Pull a list of which books are at which locations. 


