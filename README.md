# scent
method 1 - closest 3

method 2 - closest 3  with exceptions 
- if only one significant compound is too far, only 2 closest;
- If 2 or all significant compounds are too far, only 1 closest compound

method 3 - triangle (if not in a triangle, then closest 3)

method 4 - triangle (if not in a triangle, then closest 3 with exceptions)

method 5 - closest 5

method 5 - closest 5 with exceptions


methods_... - code for a pair of files, where the first file contains staring coordinates of compounds and from the second compound we take coordinates of only significant compounds as their ending coordinates to predict the shift of the insignificant compounds.

m_..._error - calculates the average error (the difference in seconds between the predicted value and the one that was clicked by hand) of 3 systems of compounds (the files were taken like that: the fist file of the experiment and the last file of the experiment in the system)
