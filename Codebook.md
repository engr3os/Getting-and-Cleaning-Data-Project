The Markdown document contains the Codebook for run_analysis.R script.
The script is used to analyze gyroscope data (sources contained in README.md) and the obtained tidy data is contained in run_analysi.txt

Each column of the text file contains the information on the measured variable while each row contains the observation for a speficic measurement. The file is stored as fixed width data and can be easily ready by the floowing code:

data <- read.table(file_path, header = TRUE)

The following are the list of the definitions of variables.
subject_id - This is the ID of the subjects that took part in the experiment
activity - This are the type of activities the subject engaged in durng the         experiment such as Laying, sitting, standing, walking upstairs, standing, walkind downstairs 

Below are the list of of gyroscope measurement made on the subjects during diffrent activities
tBodyAcc-mean()-X
tBodyAcc-mean()-Y
tBodyAcc-mean()-Z
tGravityAcc-mean()-X
tGravityAcc-mean()-Y
tGravityAcc-mean()-Z
tBodyAccJerk-mean()-X
tBodyAccJerk-mean()-Y
tBodyAccJerk-mean()-Z
tBodyGyro-mean()-X
tBodyGyro-mean()-Y
tBodyGyro-mean()-Z
tBodyGyroJerk-mean()-X
tBodyGyroJerk-mean()-Y
tBodyGyroJerk-mean()-Z
tBodyAccMag-mean()
tGravityAccMag-mean()
tBodyAccJerkMag-mean()
tBodyGyroMag-mean()
tBodyGyroJerkMag-mean()    
fBodyAcc-mean()-X
fBodyAcc-mean()-Y          
fBodyAcc-mean()-Z
fBodyAccJerk-mean()-X     
fBodyAccJerk-mean()-Y
fBodyAccJerk-mean()-Z     
fBodyGyro-mean()-X
fBodyGyro-mean()-Y         
fBodyGyro-mean()-Z
fBodyAccMag-mean()
fBodyBodyAccJerkMag-mean()
fBodyBodyGyroMag-mean()  
fBodyBodyGyroJerkMag-mean()

The attached files include:
README.md
run_analysis.R
