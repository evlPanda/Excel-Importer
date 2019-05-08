# Excel Importer

There doesn't appear to be anything in PeopleTools to import Excel files with. 

There is the PSSpreadsheet Class, but it only *creates* Excel files. There is the file import utility, but it only does csv, tab deliimited etc. (I looked at extending this, but found its overall approach too convulted; death by configuration)

This is a Keep It Simple Stupid approach to importing Excel files into a Record. You provide the file, the record, and the mapping between the two. That's it.

Drop me a line if you found this useful, and we'll form a club or something. : |
