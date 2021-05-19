**Problem -** 
This dataset (https://www.dropbox.com/s/pan6mutc5xj5kj0/trainPart1.zip) is used to train a CNN.
Next, select only 0-9 training images from the above dataset are selected and pretrained network is used to train on MNIST dataset. 
Finally, pretrained network is trained on following dataset (https://www.dropbox.com/s/otc12z2w7f7xm8z/mnistTask3.zip), test accuracy is provided on the MNIST test set, using the same test split from part 2. 


Initially before running code on google colab we have to make 3 folders manually which will contains train , test and validation data . Train , Test and Validation data is created in the code using "splitfolders" . I have used folders name as "ProcessedData" , "MNSITProcessed" and "P3" for Part 1 , Part 2 and Part 3 respectively . 

Links for dataset  - 
For Part 1 - https://www.dropbox.com/s/pan6mutc5xj5kj0/trainPart1.zip , 
For Part 2 - MNIST.zip (already uploaded in files section) , 
For Part 3 - https://www.dropbox.com/s/otc12z2w7f7xm8z/mnistTask3.zip


References - 


*   https://keras.io/api/
*   https://stackoverflow.com/
*   https://github.com/
*   https://www.geeksforgeeks.org/ 
 

Analysis for Part 2 - Pretrained network can have high convergence time , less final accuracy as compared to randomly initialized network because Pretrained network for part 1 contains large number of classes so learning will be less as compared to MNIST.zip dataset as it has less classes (roughly)
