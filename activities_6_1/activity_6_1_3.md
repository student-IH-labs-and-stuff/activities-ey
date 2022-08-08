# 6.01 Activity 3

For this activity continue with the PowerBI workbook from the previous two activities

- Get data and connect to PDF file type
- open the book_series.pdf and select to the table001 found in the pdf 
- no transformations should be needed to this file 
- the source is not integrated into the data model because there is nothing to relate it
- connect to the same excel workbook again as before, Bookshop.xls, and select only the tab **Info** to create a new source for your model 
- again, do not apply a transformation st this stage 
- because both tables share the SeriesID they should now connect 
- in order to connect into the full model you will need to transform the Info source, combining two Book ID fields together - named **BOOKID**
- create the relationship between Info and Book based on this new column 
- create a table in report view that validates the series pdf connects through the Info tab to the Book table and the rest of the model
- as an example this could be a table listing Series Name and Count of Title 
- note : it is expected that many books in the data are not connected to a Series - only a subset of books are included
