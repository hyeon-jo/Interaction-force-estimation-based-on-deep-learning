# Interaction force estimation based on deep learning
We constructed a model for learning and generating a db composed of sequential images for interaction force estimation.
## Architecture
We will release the network architecture soon.
## Dataset
We share the dataset using Google Drive.

The detail description on the database is as follows;

(1) The total number of images are 440,967 (approximately 3.6GByte) and each image is normalized into 128x128 (RGB) -pixel images for reducing the total size of the shared database.  The original database size is over 359GByte and it is not easy to share it online.

(2) The directory name is "[object]_[degree]_[illumination]"

      There are four objects, e.g., paper cup, sponge, stapler, and tube
      
      There are four degrees, e.g., 0, 10, 20, and 30 degrees
      
      There are three illuminations, e.g., 50 (350lux), 70 (550lux), 100(750lux)
      
(3) At each directory, there is "test.txt" file for GT. 

     e.g., 4,-0.00318538,0.00328883
     
             The image file name: 4.jpg
             
             The interaction force: -0.00318538
             
              Dummy: 0.00328883

Link: https://drive.google.com/open?id=1UDbevCQYvkh5kK7QfrF1NQiu4z-MJJbE
