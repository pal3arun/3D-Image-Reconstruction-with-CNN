# Deep-Learning-Internship-Summer-2019-Texas-Childrens-Hospital-Radiology-Department
Built prototype device which acquires images from 3 cameras across 60 degrees and reconstructs a 3D image of object using CNN and Synthetic Aperture Imaging

![alt text](Screenshots/Device.jpg "The Prototype Device - Automatically acquires Images using MATLAB & Arduino integrated software that controls the motor and captures images of object at defined degree intervals from multiple cameras")
The Prototype Device - Automatically acquires images using MATLAB & Arduino integrated software which captures images of object at defined degree intervals from multiple cameras.


'

![alt text](Screenshots/Device_Start_Point.jpg "The initial position from which the device acquires images at specific degree intervals")
The initial position from which the device acquires images at specific degree intervals.

'

![alt text](Screenshots/Device_End_Point.jpg "The final position that the device acquires images resulting in images captured across a range of 60 degrees.")
The final position that the device acquires images yielding an image range of 60 degrees.

'


![alt text](Screenshots/Encoder_Arduino_Determines_Angle.jpg "Encoder determines the angle of the device which is integrated with MATLAB software to enable image acquisition at precise degree intervals")
          Encoder determines the angle of the device which is integrated with MATLAB software to enable image acquisition at precise degree intervals.

'

![alt text](Screenshots/Sample_Calibration_Imageset.JPG "64 Images of checkerboard calibration object taken by the device at half-degree intervals") 
64 Images of checkerboard calibration object taken by the device at half-degree intervals.

'

![alt text](Screenshots/Arc_Design_3DModel.png "3D model of the gear arc used to move the device in small step intervals. Various components were designed using 3D Modeling Software in the creation of the device including the gear, motor structure, device reinforcement parts, phantom test object, etc. Plan to print these components in metal instead of plastic.")
          3D model of the gear arc used to move the device in small step intervals. Various components were designed using 3D Modeling Software in the creation of the device including the gear, motor structure, device reinforcement parts, phantom test object, etc. Plan to print these components in metal instead of plastic.

'
![alt text](Screenshots/Same_Particle_Diff_Cameras.png "9 neighboring images of same particle taken from different cameras at different angles (essentially different planes).") 
9 neighboring images of same particle taken from different cameras at different angles (essentially different planes). The Convolutional Neural Network aims to recognize images with focused particles. This entails determining whether the combined 9 images have a focused object and then determining the corresponding position in the image stack.

'
![alt text](Screenshots/Intensity_Center_Positions.png "One Hot Code System that determines if the combined image contains a focused object if the output node from the CNN has magnitude above the SSIM structural similarity threshold filters.") 
One Hot Code System that determines if the combined image contains a focused object if the output node from the CNN has magnitude above the SSIM structural similarity threshold filters.

'

![alt text](Screenshots/Remove_Overlap.png "Non-Maximum Suppression removes redundant overlapping particles that are considered focused by multiple combined 9-image sets. This further optimizes the smart 3d image reconstruction.")
Non-Maximum Suppression removes redundant overlapping particles that are considered "focused" by multiple combined 9-image sets. This further optimizes the smart 3d image reconstruction.

'

![alt text](Screenshots/CNN_Pipeline.png "Overall Pipeline for the Convolutional Neural Network which ultimately filters out unfocused particles thus enabling superior 3D image reconstruction")
Overall Pipeline for the Convolutional Neural Network which ultimately filters out unfocused particles thus enabling superior 3D image reconstruction.

After the CNN, the reconstruction is based on already established Synthetic Aperture Imaging methods.





***I did not include any code or details beyond general information related to the project since it may be used for further research purposes.***











