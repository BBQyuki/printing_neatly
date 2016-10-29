# Printing Neatly
Introduction to Algorithm Page 405-406

Consider the problem of neatly printing a paragraph with a monospaced font (all characters having the same width) on a printer. The input text is a sequence of n words of length l1, l2, ..., ln, measured in characters. We want to print this paragraph neatly on a number of lines that hold a maximum of M characters each. 

Our criterion of **“neatness”** is as follows. If a given line contains words i through j , where i <= j, and we leave exactly one space between words, the number of extra space characters at the end of the line is
![Equation](http://i.imgur.com/af2N82v.png)

which must be nonnegative so that the words fit on the line. We wish to minimize the sum, over all lines except the last, of the cubes of the numbers of extra space characters at the ends of lines. 

Give a dynamic-programming algorithm to print a paragraph of n words neatly on a printer. Analyze the running time and space requirements of your algorithm.
