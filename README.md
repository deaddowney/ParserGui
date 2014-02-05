ParserGui
=========

Contains the JavaFX GUI to the Parser

Offers front end for parsing FoodClub invoices into [Xero](www.xero.com) format as well as a parser front end for
converting Lancaster Farm Fresh updates in .doc format to csv for insert into [FoodClub](http://www.foodclub.org).
MS Word 2007 files will need to be converted from .docx to .doc in order to work with this parser.  This can be done in
Word by "Save As".

Dependencies
-------------
[jcfc_reporting](https://github.com/deaddowney/jcfc_reporting) does the actual parsing.  Any changes to the logic should
be made there.
