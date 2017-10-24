# Base-SAS-9.4-Programming-Prep-Guide
Contains notes for the Base SAS 9.4 Programming Prep Guide.

Here is a table of contents linking to NBViewer:
01. [Base Programming](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2001%20-%20Base%20Programming.ipynb#programs?flush_cache=true)
02. [Referencing Files and Setting Options](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2002%20-%20Referencing%20Files%20and%20Setting%20Options.ipynb?flush_cache=true)
03. [Editing and Debugging SAS Prorgams](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2003%20-%20Editing%20and%20Debugging%20SAS%20Programs.ipynb?flush_cache=true)
04. [Creating List Reports](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2004%20-%20Creating%20List%20Reports.ipynb?flush_cache=true)
05. [Creating SAS Data Sets from External Files](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2005%20-%20Creating%20SAS%20Data%20Sets%20from%20External%20Files.ipynb?flush_cache=true)
06. [Understanding DATA Step Processing](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2006%20-%20Understanding%20DATA%20Step%20Processing.ipynb?flush_cache=true)
07. [Creating and Applying User-Defined Formats](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2007%20-%20Creating%20and%20Applying%20User-Defined%20Formats.ipynb?flush_cache=true)
08. [Producing Descriptive Statistics](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2008%20-%20Producing%20Descriptive%20Statistics.ipynb?flush_cache=true)
09. [Producing HTML Output](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2009%20-%20Producing%20HTML%20Output.ipynb?flush_cache=true)
10. [Creating and Managing Variables](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2010%20-%20Creating%20and%20Managing%20Variables.ipynb?flush_cache=true)
11. [Reading SAS Datasets](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2011%20-%20Reading%20SAS%20Datasets.ipynb?flush_cache=true)
12. [Combining SAS Datasets](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2012%20-%20Combining%20SAS%20Datasets.ipynb?flush_cache=true)
13. [Transforming Data with SAS Functions](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2013%20-%20Transforming%20Data%20with%20SAS%20Functions.ipynb?flush_cache=true)
14. [Generating Data with DO Loops](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2014%20-%20Generating%20Data%20with%20DO%20Loops.ipynb?flush_cache=true)
15. [Processing Variables with Arrays](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2015%20-%20Processing%20Variables%20with%20Arrays.ipynb?flush_cache=true)
16. [Reading Raw Data in Fixed Fields](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2016%20-%20Reading%20Raw%20Data%20in%20Fixed%20Fields.ipynb?flush_cache=true)
17. [Reading Free-Format Data](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2017%20-%20Reading%20Free-Format%20Data.ipynb?flush_cache=true)
18. [Reading Date and Time Values](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2018%20-%20Reading%20Date%20and%20Time%20Values.ipynb?flush_cache=true)
19. [Creating a Single Observation from Multiple Records](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2019%20-%20Creating%20a%20Single%20Observation%20from%20Multiple%20Records.ipynb?flush_cache=true)
20. [Creating Multiple Observations from a Single Record](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2020%20-%20Creating%20Multiple%20Observations%20from%20a%20Single%20Record.ipynb?flush_cache=true)
21. [Reading Hierarchical Files](https://nbviewer.jupyter.org/github/JLeeHPA/Base-SAS-9.4-Programming-Prep-Guide/blob/master/Chapter%2021%20-%20Reading%20Hierarchical%20Files.ipynb?flush_cache=true)

Notes for the test:
* When a question asks how many steps (DATA or PROC) an example code has, count the number of times DATA and PROC appears
*	When a question asks how many statements an example code has, count the number of semicolons that appear
*	If a question asks how to specify output in any OS, use programming statements to do so
*	When SAS reads 4-year dates from sources/informats, YEARCUTOFF = does not affect the reading of the year, but it does affect the reading of 2-year dates
*	An engine is a set of internal instructions that SAS uses for writing to and reading from files in a SAS library. Specifies the file format that is used by a particular file
*	Base SAS exam wants you to check the log window 1st after every code submission, then check the results window
*	When using PROC PRINT and invoking the SUM statement, column totals use the same format as the variables
*	Syntax error checking DOES NOT verify the values of variables or the correctness of formats
*	When SAS cannot detect syntax errors, the DATA step compiles but does not execute
*	User-defined formats must begin with ‘$’ if applied to char variables
*	For questions regarding which format to choose, choose the most appropriate format with the largest width allowable
*	For questions regarding strings and length when there is an automatic conversion from numeric to character, SAS chooses the BEST12. format
*	If variable undefined:	x + 1; <- produces numeric values, turns missing numeric values into 0,	x = x + 1; <- produces missing values
*	The MEAN function will ignore missing values and just count the ones that aren’t missing
*	For questions using POINT = , POINT = needs to be equal to a variable name, not just an observation integer
*	If reading inline external file, use COMMAW.D format to read any numbers with commas (,) or dollar-signs ($), or else will return missing
*	Date formats have to be written as  ‘DDMMMYYYY’d, like so: ‘01JAN2017’d
*	Every input statement will move the pointer down a line
