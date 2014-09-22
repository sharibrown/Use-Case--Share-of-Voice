How to connect to your source JSON files:

1.   Click on the file input module and configure the input data source.  
2.   File browse for all file types (*.*) -  it defaults to all data files.
3.   Click on one of your files to set the path.
4.   Read the file as a built in type "Comma Delimited Text File".
6.   Delimit with \0
7.   Set the field length to 999999
8.   1st row is not field names (leave this box unchecked)
9.   Alter the path to read all JSON files in this directory by using the wildcard operator.  \SOV*.* 
10.  Go through the format steps above again.
11.  Be sure you don't have anything other than JSON files in this path or the process will fail.

Taking JSON payloads and translating them into key-value pairs consumes a lot of space.  For this example a 612MB JSON file turned into 2.5GB in the pre-process before the filter tool is applied. 


