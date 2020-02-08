# Image-Compression
Compressing an image using K-Means clustering algorithm

Image compression plays a major role during image transmission and storage.
This reduces the usage of higher bandwidth and hard disk space.

This project has been developed in java by using K- Means Clustering algorithm. 
-------------------------------------------------------------------------------------------
To run the code, use the below commands:

/> javac ./kmeans/Kmeans.java
/> java kmeans/Kmeans <original file path> <compressed file name> <K value>
  
Example:
/> java kmeans/Kmeans koala.jpg koala 15.jpg 15
<Compressed file name> represents the name of the compressed image file you want to create.

Output:
A new file is created in the directory with above mentioned name "koala 15".
