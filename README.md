# P-resolutions

There are three files.

## continued fractions 0
One uses this to find all continued fractions representing 0 up to a certain length, and store it in a txt file. It has been observed that the file is practical for length at most 14, beyond which the txt file becomes huge.

## Find All P resolutions
Given a cyclic quotient singularity, this helps to find all the p-resolutions of it by running the algorithm given in Altman's paper. Note that this uses the txt file created using the "continued fractions 0" code.

## Check P resolution
Given the intersection matrix of an exceptional locus, this can be used to check if contraction of certain curves gives a p-resolution. Other things such as rationality, calculation of K^2 etc. are all part of the information this prints.
