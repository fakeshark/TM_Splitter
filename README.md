# TM_Splitter
Application that splits a large XML, SGML, or text document into smaller files.


document file needs to have the following lines (split marker) at the split:

<!--
nurseryRhyme5.txt
SplitHere--> 

this should be where the split is intended to take place.
format must be exactly as show.
opening comment tag on it's own line,
the next line is what will become the file name for everything that came before this split marker,
and then the last part should be on it's own line.

