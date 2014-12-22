<h1>Codebook for the Coursera Data Cleaning Course</h1>

The data used in this assignment came from the UC Irvine Machine Learning Repository. A description of the research study from which the data originated can be found here: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones. There are 561 points of cell phone acceleromator data taken from the cell phones worn by the study's 30 participants which are listed here: https://github.com/mgiorno/CourseraDataCleaningProject/edit/master/features.txt. These data were used to plot the movement of each particpant while they wore the cell phone.

In adition to the acceleromator data each participant's id number, an activity id number and a descriptive label for each type of activity was collected with the triaxial data to summarize the findings both by subject and by the type of activity they were engaged in when each record of 3-d spatial and body movement data was collected.

The six different activity types and their numeric index are as follows:

<table>
<tr><td><b>ActivityID</b></td><td><b>ActivityLabel</b></td></tr>
<tr><td>1</td><td>WALKING</td></tr>
<tr><td>2</td><td>WALKING_UPSTAIRS</td></tr>
<tr><td>3</td><td>WALKING_DOWNSTAIRS</td></tr>
<tr><td>4</td><td>SITTING</td></tr>
<tr><td>5</td><td>STANDING</td></tr>
<tr><td>6</td><td>LAYING</td></tr>
</table>

The data was initially divided into two files. One was a test data set and the other was a training data set. The training set is made up of a random samply of 70% of the particpants and the test set is the data from the other 30% of the participants. Both sets have been combined to create a cleaned subset of statistical means calculations for 79 the mean and standard deviation data points or variables from the parent set of 561. These means where calculated by activity type and by participant.


These data were gieven the the instructors by the researchers at UCI Machine Repository for use as instructional classroom. Below is the proper attribution of the originl source data:


<b>Source:</b>

Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto.
Smartlab - Non Linear Complex Systems Laboratory
DITEN - UniversitÃ  degli Studi di Genova, Genoa I-16145, Italy.
activityrecognition '@' smartlab.ws
www.smartlab.ws
