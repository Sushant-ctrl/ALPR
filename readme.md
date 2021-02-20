# ALPR Automatic Licence Plate Detection 


This is an Industrial Project with real life application. The system was build at Electronics and Communication Engineering Department of Visveswaraya National Institute of Technology Nagpur, Under the guidance and mentorship of Prof. Snigdha Bhagat.

### Results

### Algorithms and technology used
This project involved implementation and understanding of the following technology.

* **Object Detection and Localisation Algorithms**
    This involved going through various algorithms like RCNN, fast RCNN, and YOLO algorithms. Finally after reading these algorithms and getting an insight on working and outcomes of each one it was decided to go with **YOLO algorithm** for the detection part.
* **OCR Models**
    OCR is the heart of this project as after finding the lisence plate we need to read what is written on it. 
* **GAN Models**
    GANs are used to generate dataset for adverse weather condition. We used **style transfer GAN** to genereate fog and rain affected images for training. However training was carried out only on fog affected images as the rain style images didn't give appropriate output.
* **Super Resolution Models**
    Super resolution models are used to improve the pixel density in the cropped numberplate images that are being passed into the OCR model.



### Using this repository

### Loading our Pretrained Weights

<!-- ### Pipeline of the project

* Literature study 
* Understanding of the problem setting
* Implementation of various State of The Art Technology check the feasiblity
* 
 -->