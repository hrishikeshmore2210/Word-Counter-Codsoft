# Word-Counter-Codsoft

This program counts the number of lines, number of words and number of characters in the specified file. We will be declaring two functions called wordcount and linecount in the program. The function linecount has been overloaded according to the passing argument. If you input contents through the file then linecount function will be called (If specified file exists) otherwise main function counts the number of characters and number of lines (always, the number of line will be only 1 in this condition) itself but for the counting of the number of words by using the wordcount function.

**wordcount(String line)**

The function wordcount(String line) takes either the content of the specified file or arguments passed with the run command for a java program as parameter 'String line'. The wordcount() function is using arrayname.charAt(index) to find position of space in the string.  A counter variable 'numWords' is used to count the number of words.

**linecount(String fileName);**

The function linecount(String fileName) takes the specified file name as a string parameter and create a instance for the FileReader class to buffering then the file or string and it is passed to the function linecount(String fName, BufferedReader in).

**linecount(String fileName, BufferedReader);**

The function linecount(String fName, BufferedReader in) takes the specified file name and created instance in for the BufferedReader class by calling function linecount(String fileName) and assign the content of the buffer in a string variable line. And then the function linecount(String fileName, BufferedReader) counts and print the number of characters, number of lines. To count the number of words call the wordcount(String line) function.
