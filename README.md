# Learn-Python

# First assignment
### Install python, recommend https://www.continuum.io/downloads , suggest 64 bit version 2.7
### Down load VS Code https://code.visualstudio.com/Download 
### Add the directory with python.exe from install #1 above to system path (if it isn't already)
### Create a python program that print Hello World
### Create a repository in GitHub.com, upload your python code and mail me the url
## Important: Ask questions if you get stuck

# Rule G-33 Challenge:  DUE DATE TUESDAY JULY 18TH
 
A successful program will:

Prompt the user for two inputs: 
A letter indicating if the user will input Accrued Interest, Dollar Price, or Yield (i.e., “A”, “D”, or “Y”)
A number
Upon entering the two inputs, the program will perform a rounding function consistent with the Standards of Accuracy; Truncation rounding rules of MSRB Rule G-33 (below)
Bonus: user can continue entering numbers repeatedly, but has a way to exit when boredom threshold is exceeded
 
Tips:
Each of the three rounding rules should have its own function
The program should pass the number to the correct function within the program
Do not worry about handling invalid inputs – assume the user will only enter valid inputs
Programmers who attempt to complete the assignment during the meeting will be buying for the others on coffee runs
 
 
 
Rule G-33
Standards of Accuracy; Truncation.
(i) Intermediate Values. All values used in computations of accrued interest, yield, and dollar price shall be computed to not less than ten decimal places.
(ii) Results of Computations. Results of computations shall be presented in accordance with the following:
(A) Accrued interest shall be truncated to three decimal places, and rounded to two decimal places immediately prior to presentation of total accrued interest amount on the confirmation;
(B) Dollar prices shall be truncated to three decimal places immediately prior to presentation of dollar price on the confirmation and computation of extended principal; and
(C) Yields shall be truncated to four decimal places, and rounded to three decimal places, provided, however, that for purposes of confirmation display as required under rule G-15(a) yields accurate to the nearest .05 percentage points shall be deemed satisfactory.
Numbers shall be rounded, where required, in the following manner: if the last digit after truncation is five or above, the preceding digit shall be increased to the next highest number, and the last digit shall be discarded.

# Attached is csv file with Apple stock weekly trading values.

Unfortunately it is in US dollars. I need the five columns containing dollar values in UK Pounds instead.

In Euros.

Hint: the open() function can be used to open text files, the 'rb' option is probably required.
Hint 2: import csv and use the csv.reader() function to read the data or the csv.DictReader() to use the header names to read the data for each row. 
Hint 3: Google is your friend.

Extra credit: Output in ancient imaginary currency Roman stones. 1 Rock = 1 dollar, 1 pebble in 10 cents, must be expressed in Roman numerals. So $112.50 = "CXII rocks and V pebbles". Formatted just like that. No need to worry about values over $2000 or negative values. No fractional pebbles, sand is worthless, truncate down to whole pebbles. Remember there is no zero in Roman numerals. So we use the special value NO, $0.00 = "NO rocks". If we have a value with no pebbles we omit it from the printed value.

As with other challenge, post your solution to GitHub and send me the link. If you get stuck ask questions.