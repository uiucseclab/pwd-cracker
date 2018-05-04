# pwd-cracker

python main.py -- runs main TUI program

Check the includes section at the top of main.py to make sure all necessary python libraries are installed.

Also, in order to certain non-ascii characters to be displayed make sure you terminal/shell are set to UTF8 encoding

Feel free to change the global LIMIT, variable at the top of the file as it controls how long each password cracking function will runbefore giving up. 

The relevant code is all in main.py, and it broken into several functions, which have short descriptions and comments in them.

Overall, the code contains several functions which all aim to crack or assist in cracking passwords. As opposed to my original project statement I went with more of a statistical analysis approach then a full blown machine learning approach. Mainly because of a lack of data.

Inside main.py there is a function called main() which will be run by default when you execute "python main.py", and it showcases the basic features of "brute\_force", "freq\_force", and "indiv\_freq\_force" functions. In addition there are several functions and sections of example code that I've commented out. Inside of the main() function there is plotting code to demonstrate the ability to find all the most commonly occuring substrings of a given length or all substrings of any length. Also, there is a test() function with various examples given that you can use to try out the functions now in main(). I have commented out the call to test() at the bottom of the file, but just uncomment that and comment out main() to try it out.

I think to make the most out of the tools it is best to tweak the options and view the different plots to investigate what works best. So I intend it less of a machine learning tool, and more of a statistical analysis tool for someone to use in addition to other methods to crack passwords.
