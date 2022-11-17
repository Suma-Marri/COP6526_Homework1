# COP6526_Homework1

Please implement a Map/Reduce program on PySpark. 

The input text is available at the file input.txtDownload input.txt

For each word in the input text, please compute the occurrences of other words appearing in the same line. For example, assume that we have the following line as an input text. For this assignment, you are going to compute the occurrences of every word for all lines, not just for a single line.

I had seen little of Holmes lately. My marriage had drifted us

With the word "I",

 - "had" occurs twice.
 - "seen" occurs once.
 - "little" occurs once.
  and so on.

With the word had,

 - "I" occurs once.
 - "had" occurs once. (not zero times!)
  and so on.

You must follow these guidelines to obtain the correct result.

 - Convert every string into lower-case.
 - Remove all punctuation, i.e., any character other than a to z and space. It will be helpful to use a regular expression to replace them with empty strings. Of course, this will result in some non-sense situations (im, youre, and etc.), but you do not have to worry about this.
