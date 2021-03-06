# Fix-Align

Software for the automatic correction of recorded eye fixation locations in reading experiments.<br>
Andrew L. Cohen

Behavior Research Methods<br>
September 2013, Volume 45, Issue 3, pp 679-683

Because the recorded location of an eyetracking fixation is not a perfect measure of the actual fixated location, the recorded fixation locations must be adjusted before analysis. Fixations are typically corrected manually. Making such changes, however, is time-consuming and necessarily involves a subjective component. The goal of this article is to introduce software to automate parts of the correction process. The initial focus is on the correction of vertical locations and the removal of outliers and ambiguous fixations in reading experiments. The basic idea behind the algorithm is to use linear regression to assign each fixation to a text line and to identify outliers. The freely available software is implemented as a function, Fix_Align.R, written in R.
