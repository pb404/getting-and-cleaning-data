Here's how my R analysis script works:

A. STEP ONE:

- First the script reads in the training data first into X\_train and Y\_train.I bind them by column with my Y\_train column coming first.Then I read the subject variable and . So my subject and activity columns will come first followed by all the variables.(I assume that the folder UCI HAR Dataset is already in my working directory)    [Lines 1-5]
- Then the script does the same steps for the testing data. [Lines 10-14]
- Finally the script completes the first step of the assignment in Line 17 of the code when it row binds the training and testing data.

B. STEP TWO:

- Now the script searches for the column names which have mean or standard deviation (using the grep function).
- Then I subset the relevant columns. I add 2 to the col list I obtained because my first 2 columns are subject and activity.

C. STEP THREE:

- First the script renames the first 2 columns as subject and activity.[Line 25]
- Then the pylr library is used to access the revalue function which allows me to rename the factors of the activity column [Line 26-28].

D. STEP FOUR:

- Lines 31-46 are basically substituting various substrings to get a relevant long variable names.

E. STEP FIVE:

- Finally the line 49 creates the tiny data with the help of the aggregate function. The final dimensions of the tinydata is 180\*68.


So finally we have data set in which the mean and standard deviation of all the signals for all the subjects and activities is obtained. All subjects performed all activities. The study had 30 subjects and 6 activities(listed in the codebook).