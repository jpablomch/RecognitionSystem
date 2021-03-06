# Image Recognition of Disease-Carrying Insects: A System for Combating Infectious Diseases using Image Classification Techniques and Citizen Science

## Related Publication
### If you use part of this code or extend the applications developed for this project, please cite: 

[J. Pablo Muñoz, Rebecca Boger, Scott Dexter, Russane Low, and Justin Li. **Image Recognition of Disease-Carrying Insects: A System for Combating Infectious Diseases using Image Classification Techniques and Citizen Science**, in The Hawaii International Conference on System Sciences (HICSS-51), 2018.](https://scholarspace.manoa.hawaii.edu/bitstream/10125/50247/1/paper0360.pdf) **Best Paper Award**

[![Recognition System Video](http://img.youtube.com/vi/iTjd30SCaqQ/hqdefault.jpg)](https://youtu.be/iTjd30SCaqQ?rel=0)

## Android Applications 

### Image Collector 

[Here](https://github.com/jpablomch/ImageCollector)

### Recognition Client

[Here](https://github.com/jpablomch/RecognitionClient)

### Expert Validation

[Here](https://github.com/jpablomch/ExpertValidation)

## Python Applications

### Recognition Server

[Here](https://github.com/jpablomch/RecognitionServer)

## Prerequisites and Dependencies 

[***Caffe***](http://caffe.berkeleyvision.org/) - Training the model requires the *Caffe Deep Learning* framework. 
The *Recognizer Server* application requires the Python wrappers for *Caffe*. 

[***OpenCV***](http://opencv.org/) - The recognition server uses *OpenCV* for processing images. 

[***Dropbox***](http://dropbox.com) - You need to generate your own keys from *Dropbox* to access your remote folders.

[***DynamoDB***](https://aws.amazon.com/dynamodb/) - We want to move from *Dropbox* to some more scalable platform. We have done some initial work using a more scalable solution like *DynamoDB*.

## Tutorial on training a model

[Here]() TODO

## Contributing to the project

TODO

**This work was supported by NSF EAGER #1645154**
