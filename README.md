# Portfolio

# Recent Projects

# [Style Transfer](https://github.com/theinthankhaing/Style-Transfer)

* Implemented this project based on paper titled, ["Image Style Transfer Using Convolutional Neural Networks"](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)
* Take a content image and a style image 
* Produce a new image which reflects the content of the content image but the artistic "style" of the style image
* Calculate the loss function (combination of content loss and style loss) which matches the content and style of each respective image in the feature space
* Perform gradient descent on the pixels of the image itself
* Pre - trained deep neural network, [SqueezeNet](https://arxiv.org/abs/1602.07360) is used
* CPU is used
* Pytorch is used



# Projects done in 2020

# [IoT Project with AWS Cloud Platform](https://github.com/theinthankhaing/IoT-Project-with-AWS-Cloud-Platform)

* Push [jet engine data](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan) to AWS
* Record those data inAWS IoT and Visualize them
* Use AWS services, such as Lambda Function, SNS

# [Indoor Positioning System](https://github.com/theinthankhaing/Kalman-Filter-Project)

* Position is estimated by designing Kalman filter to reduce the effect of noise

# [Computation Offloading for IoT Devices using Mobile-Edge Computing](https://github.com/theinthankhaing/Computation-Offloading-for-IoT-Devices-using-Mobile-Edge-Computing)

* Make Survey on three algorithms of computation algorithms: LODCO, RLO and DPCOEM
* Comparison of those three algorithm based on thier energy consumption and execution time

# [Generate Anime using trained CartoonGAN](https://github.com/theinthankhaing/CartoonGAN)

* Implemented by reading paper named ["CartoonGAN: Generative Adversarial Networks for Photo Cartoonization"](https://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_CartoonGAN_Generative_Adversarial_CVPR_2018_paper.pdf) and [GitHub repository](https://github.com/mnicnc404/CartoonGan-tensorflow?fbclid=IwAR2OpOh8hlc62EFxXpkeGDA5UV8CzxcXUKo8-JqtLoUvmb7gAYgjglRPU1Q)
* Changing photo or giphy into cartoon style images
* Google Colab is used
* Tensorflow is used

# [Energy - Efficient Scheduling Algorithm to Reduce CPU Power Consumptions for Periodic Tasks in Real - Time Embedded System](https://github.com/theinthankhaing/Real-Time-Scheduling-Algorithm-Implementation)

* Implemented Dynamic Voltage and Frequency Scaling (ES - DVFS) and Dynamic Global Energy - Efficent Scheduling Based on the Actual Execution Time (DGAET) by reading papers
* Compared these two algorithms

# [Pattern Recognition Using Eigen Digits](https://github.com/theinthankhaing/Pattern-Recognition-Using-Eigen-Digits)

* MNIST digit dataset is used
* Eigen values and eigen vectors are calculated
* Reconstructed Handwritten digits
* Classification using Linear Regression
* Classification using Polynomial Regression
* MATLAB is used

# [SVM for Classification of Spam Email Messages](https://github.com/theinthankhaing/SVM-for-Classification-of-Spam-Email-Messages)

* Spam Dataset is used
* Pre - processed data using Standardization
* Created own SVM
* Calculated the Accuracy
* MATLAB is used

# [Q-Learning for World Grid Navigation](https://github.com/theinthankhaing/Q-Learning-for-World-Grid-Navigation)

* Implement Q - learning algorithm
* Make the robot reach the goal by maximizing the total reward of the trip
* Make Q-function converge to the optimal values
* MATLAB is used

# Projects Done in 2019

# [Head-Pose-Classification-and-Isolated-Word-Recognition-with-Vibration-of-Vocal-Folds-while-Talking](https://github.com/theinthankhaing/Head-Pose-Classification-and-Isolated-Word-Recognition-with-Vibration-of-Vocal-Folds-while-Talking)

* Accumulated audio voices of Isolated Japanese words and head positions from both male and female using Throat microphone
* Labelled the audio with head postions
* Performed Resampling and normalization as a preprocessing
* Both speech recognition and head postion classification are performed by using the vibration of speech signals recorded by Throat Microphone
* CNN is used for classification
* Python 3.6 and Tensorflow 2

# Projects Done in 2018

# [Implementation of Speech Recognition System for Security Purposes](https://github.com/theinthankhaing/Implementation-of-Speech-Recognition-System-for-Security-Purposes)

* Implemented Speaker Dependent Isolated Word Speech Recognition based Securtiy System using MATLAB and Arduino UNO
* Recorded  6 words  with different syllables  
* Preprocessed these words using combination of zero-crossing rate (ZCR) and Energy Calculation
* Extracted features using Mel-Frequency Cepstral Coefficients (MFCC)
* Performed feature training and recognition using Vector Quantization (VQ) and Dynamic Time Warping (DTW)
* Built a prototype of house and  attached the door, which is automated by using ARDUINO controlling servo motor
* Sent the recognized output from MATLAB to ARDUINO using Bluetooth and  ARDUINO performed open and close of the door based on the recognition ouput
* Obtained 90% of recognition accuracy for the user by using Vector Quantization for recognition
