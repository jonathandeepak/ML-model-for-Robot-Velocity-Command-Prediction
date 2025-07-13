+The code is submitted as a jupyter notebook

Environment Used- PyCharm running inside anaconda env

Dependencies 
All required libraries and dependencies are listed in the requirements.txt file

No datasets are being submitted with the code:

Training Dataset was taken from Training/Open_Box_CSV_files. The entire folder was used as train data
Test Dataset was taken from Testing. Only the first 6 files containing the name Aug_Box were used as the other files were from different environment(Corridor)

In the code folder "vel_v" is the file which predicts the linear velocity command and "vel_w" predicts angular velocity command since regression can only give one output, two models are being used to predict the 2 target variables. 