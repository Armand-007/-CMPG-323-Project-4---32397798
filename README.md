# -CMPG-323-Project-4---32397798
In Project 4 we used UIPath to automate user acceptance testing.
## How the program works and how to use it
1) The Sequence starts with and Excel application scope that reads the data from the Excel file.
2) Get workbook sheets activity is used to get the sheets in the Excel file and add them to a list, "ListOfSheets".
3) A for-loop is used to iterate through the sheets in the list.
4) The data is read into a data table(dtData) and Orchestrator is used to securely save the login information.
5) The Browser is opened and the webpage is checked by the program to see if login is required.
6) If login is needed the needed information is retrieved from Orchestrator and entered in the requiered fields.
7) The program will the check the sheet name and enter the data in the associated fields where they are needed.
8) A "For-each-row-in-datatable" activity is used to iterate the sheet row by row and enter the data on the web page.

To use the program the user only needs to run it, as everything is automated UIPath will enter all the needed information.
