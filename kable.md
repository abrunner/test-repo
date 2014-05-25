|Variable Name|Variable type|Values (range of values for numeric)|Description|
|:--------------------------|:--------------|:-----------|--------------------------------------------------------------------------------------------------:|
|subject|integer|1-30|Subject id numbers (n=30)|
|activity|factor|walking, walkingupstairs, walkingdownstairs, sitting, standing, laying|Activity: walking, walking upstairs, walking downstairs, sitting, standing, laying|
|group|factor|test or train|subject assigned to either test group or train group|
|tBodyAcc.mean.X|numeric|0.222   0.301|mean of body acceleration raw signals (time domain), x coordinate|
|tBodyAcc.mean.Y|numeric|-0.001   -0.041|mean of body acceleration raw signals (time domain), y coordinate|
|tBodyAcc.mean.Z|numeric|-0.075   -0.153|mean of body acceleration raw signals (time domain), z coordinate|
|tBodyAcc.std.X |numeric|-0.009   0.627|standard deviation of body acceleration raw signals (time domain), x coordinate|
|tBodyAcc.std.Y |numeric|-0.002   0.617|standard deviation of body acceleration raw signals (time domain), y coordinate|
|tBodyAcc.std.Z |numeric|-0.008   0.609|standard deviation of body acceleration raw signals (time domain), z coordinate|
|tGravityAcc.mean.X|numeric|-0.135   0.975|mean of gravity acceleration raw signals (time domain), x coordinate|
|tGravityAcc.mean.Y|numeric|-0.003   0.957|mean of gravity acceleration raw signals (time domain), y coordinate|
|tGravityAcc.mean.Z|numeric|-0.002   0.958|mean of gravity acceleration raw signals (time domain), z coordinate|
|tGravityAcc.std.X|numeric|-0.830   -0.997|standard deviation of gravity acceleration raw signals (time domain), x coordinate|
|tGravityAcc.std.Y|numeric|-0.644   -0.994|standard deviation of gravity acceleration raw signals (time domain), y coordinate|
|tGravityAcc.std.Z|numeric|-0.610   -0.991|standard deviation of gravity acceleration raw signals (time domain), z coordinate|
|tBodyAccJerk.mean.X|numeric|0.043   0.130|mean of body acceleration jerk raw signals (time domain), x coordinate|
|tBodyAccJerk.mean.Y|numeric|-0.011   0.010|mean of body acceleration jerk raw signals (time domain), y coordinate|
|tBodyAccJerk.mean.Z|numeric|-0.010   0.009|mean of body acceleration jerk raw signals (time domain), z coordinate|
|tBodyAccJerk.std.X|numeric|-0.004   0.544|standard deviation of body acceleration jerk raw signals (time domain), x coordinate|
|tBodyAccJerk.std.Y|numeric|-0.012   0.355|standard deviation of body acceleration jerk raw signals (time domain), y coordinate|
|tBodyAccJerk.std.Z|numeric|-0.014   0.031|standard deviation of body acceleration jerk raw signals (time domain), z coordinate|
|tBodyGyro.mean.X|numeric|-0.003   0.193|mean of body gyroscope raw signals (time domain), x coordinate|
|tBodyGyro.mean.Y|numeric|-0.002   0.027|mean of body gyroscope raw signals (time domain), y coordinate|
|tBodyGyro.mean.Z|numeric|0.000   0.179|mean of body gyroscope raw signals (time domain), z coordinate|
|tBodyGyro.std.X|numeric|-0.026   0.268|standard deviation of body gyroscope raw signals (time domain), x coordinate|
|tBodyGyro.std.Y|numeric|-0.015   0.477|standard deviation of body gyroscope raw signals (time domain), y coordinate|
|tBodyGyro.std.Z|numeric|-0.031   0.565|standard deviation of body gyroscope raw signals (time domain), z coordinate|
|tBodyGyroJerk.mean.X|numeric|-0.022   -0.157|mean of body gyroscope jerk raw signals (time domain), x coordinate|
|tBodyGyroJerk.mean.Y|numeric|-0.013   -0.077|mean of body gyroscope jerk raw signals (time domain), y coordinate|
|tBodyGyroJerk.mean.Z|numeric|-0.007   -0.092|mean of body gyroscope jerk raw signals (time domain), z coordinate|
|tBodyGyroJerk.std.X|numeric|-0.164   0.179|standard deviation of body gyroscope jerk raw signals (time domain), x coordinate|
|tBodyGyroJerk.std.Y|numeric|-0.015   0.296|standard deviation of body gyroscope jerk raw signals (time domain), y coordinate|
|tBodyGyroJerk.std.Z|numeric|-0.034   0.193|standard deviation of body gyroscope jerk raw signals (time domain), z coordinate|
|tBodyAccMag.mean|numeric|-0.001   0.645|mean of body acceleration signals (time domain), Euclidean norm magnitude|
|tBodyAccMag.std|numeric|-0.014   0.428|standard deviation of body acceleration signals (time domain), Euclidean norm magnitude|
|tGravityAccMag.mean|numeric|-0.001   0.645|mean of gravity acceleration signals (time domain), Euclidean norm magnitude|
|tGravityAccMag.std|numeric|-0.014   0.428|standard deviation of gravity acceleration signals (time domain), Euclidean norm magnitude|
|tBodyAccJerkMag.mean|numeric|-0.018   0.434|mean of body acceleration jerk signals (time domain), Euclidean norm magnitude|
|tBodyAccJerkMag.std|numeric|-0.020   0.451|standard deviation of body acceleration jerk signals (time domain), Euclidean norm magnitude|
|tBodyGyroMag.mean|numeric|-0.003   0.418|mean of body gyroscope signals (time domain), Euclidean norm magnitude|
|tBodyGyroMag.std|numeric|-0.022   0.300|standard deviation of body gyroscope signals (time domain), Euclidean norm magnitude|
|tBodyGyroJerkMag.mean|numeric|-0.046   0.088|mean of body gyroscope jerk signals (time domain), Euclidean norm magnitude|
|tBodyGyroJerkMag.std |numeric|-0.044   0.250|standard deviation of body gyroscope jerk signals (time domain), Euclidean norm magnitude|
|fBodyAcc.mean.X|numeric|-0.023   0.537|mean of body acceleration raw signals (frequency domain), x coordinate|
|fBodyAcc.mean.Y|numeric|-0.006   0.524|mean of body acceleration raw signals (frequency domain), y coordinate|
|fBodyAcc.mean.Z|numeric|-0.048   0.281|mean of body acceleration raw signals (frequency domain), z coordinate|
|fBodyAcc.std.X |numeric|-0.005   0.659|standard deviation of body acceleration raw signals (frequency domain), x coordinate|
|fBodyAcc.std.Y |numeric|-0.003   0.560|standard deviation of body acceleration raw signals (frequency domain), y coordinate|
|fBodyAcc.std.Z |numeric|-0.034   0.687|standard deviation of body acceleration raw signals (frequency domain), z coordinate|
|fBodyAccJerk.mean.X|numeric|-0.007   0.474 |mean of body acceleration jerk raw signals (frequency domain), x coordinate|
|fBodyAccJerk.mean.Y|numeric|-0.003   0.277 |mean of body acceleration jerk raw signals (frequency domain), y coordinate|
|fBodyAccJerk.mean.Z|numeric|-0.025   0.158 |mean of body acceleration jerk raw signals (frequency domain), z coordinate|
|fBodyAccJerk.std.X|numeric|-0.004   0.477 |standard deviation of body acceleration jerk raw signals (frequency domain), x coordinate|
|fBodyAccJerk.std.Y|numeric|-0.002   0.350 |standard deviation of body acceleration jerk raw signals (frequency domain), y coordinate|
|fBodyAccJerk.std.Z|numeric|-0.006   -0.993|standard deviation of body acceleration jerk raw signals (frequency domain), z coordinate|
|fBodyGyro.mean.X|numeric|-0.030   0.475 |mean of body gyroscope raw signals (frequency domain), x coordinate|
|fBodyGyro.mean.Y|numeric|-0.056   0.329 |mean of body gyroscope raw signals (frequency domain), y coordinate|
|fBodyGyro.mean.Z|numeric|-0.011   0.492 |mean of body gyroscope raw signals (frequency domain), z coordinate|
|fBodyGyro.std.X|numeric|-0.108   0.197|standard deviation of body gyroscope raw signals (frequency domain), x coordinate|
|fBodyGyro.std.Y|numeric|-0.028   0.646|standard deviation of body gyroscope raw signals (frequency domain), y coordinate|
|fBodyGyro.std.Z|numeric|-0.082   0.522|standard deviation of body gyroscope raw signals (frequency domain), z coordinate|
|fBodyAccMag.mean|numeric|-0.004   0.587|mean of body acceleration signals (frequency domain), Euclidean norm magnitude|
|fBodyAccMag.std|numeric|-0.021   0.179|standard deviation of body acceleration signals (frequency domain), Euclidean norm magnitude|
|fBodyBodyAccJerkMag.mean|numeric|-0.013   0.538|mean of body acceleration jerk signals (frequency domain), Euclidean norm magnitude|
|fBodyBodyAccJerkMag.std|numeric|-0.014   0.316|standard deviation of body acceleration jerk signals (frequency domain), Euclidean norm magnitude|
|fBodyBodyGyroMag.mean|numeric|0.000   0.204|mean of body gyroscope signals (frequency domain), Euclidean norm magnitude|
|fBodyBodyGyroMag.std|numeric|-0.061   0.237|standard deviation of body gyroscope signals (frequency domain), Euclidean norm magnitude|
|fBodyBodyGyroJerkMag.mean|numeric|-0.023   0.147|mean of body gyroscope jerk signals (frequency domain), Euclidean norm magnitude|
|fBodyBodyGyroJerkMag.std|numeric|-0.040   0.288|standard deviation of body gyroscope jerk signals (frequency domain), Euclidean norm magnitude|
