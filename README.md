# SQL-Library-Management-System
Steps to create a database:
1. create a database and use that database to create and call the procedures.
2. copy&paste the procedure present in Creating DB&Tsbles.txt in sql workbench and call the procedure.
3. copy&paste the pocedures present in Procedures.txt file and run each procedure once to create the procedures in the database.
4. Now, we can start calling the procedures.

procedures present are:
1. bookCopiesAtAllSharpstown ( IN bookTitle VARCHAR(70), IN branchName VARCHAR(70) )
2. bookCopiesAtAllBranches( IN bookTitle VARCHAR(70) )
3. NoLoans()
4. LoanersInfo ( IN DueDate DATE, IN LibraryBranchName VARCHAR(50) )
5. TotalLoansPerBranch( )
6. BooksLoanedOut ( IN BooksCheckedOut INT )
7. BookbyAuthorandBranch ( IN BranchName VARCHAR(50), IN AuthorName VARCHAR(50) )
