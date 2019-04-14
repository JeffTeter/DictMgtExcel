Multivalue Dictionary Management with Excel

This project provides a means of managing dictionaries for multivalue systems
using a set of dictionaries for extracting based on work by Brian Leach. 
The source dictionaries are saved in a delimited file which the user may edit 
after loading into Excel. After all changes are made, a delimited file is saved 
and the user may upload the changes to one or more dictionary files. 

Dictionary types supported 
    A   Pick systems attributes 
    D   UniVerse data definitions 
    I   UniVerse interpreted
    PH  UniVere phrases
    S   Picy system synonyms
    X   User defined variables 

DICT_GROUP

A unique ability of this method is the provision for the user to define
dictionary groups. For instance, when a file is created a default dictionary 
file is created. This is referred to as the base dictionary. The user may 
create additional dictionaries for specific purposes, e.g., ODBC, using the 
"CREATE-FILE DICT filename" syntax. Using a bit-wise technique, if we refer to 
the base as "1" and the ODBC dictionary set as "2", then an individual dictionary
that we want to appear in both would be assigned a DICT_GROUP value of "3" (the
sum of "1" and "2"). 

In this way, we can edit multiple sets of dictioanries in our Excel workbook, 
reducing duplication and assuring consistency in formatting, naming and structure. 


