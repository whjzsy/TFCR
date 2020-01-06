The matlab code for TFCR tracker.

The code also can be downloaded [here](https://drive.google.com/open?id=1DCou-KvSj9joI68KwynWGIzJ3XY-lr06) or [here]().

## TFCR
Learning Target-focusing Convolutional Regression Model for Visual Object Tracking

was submited to Knowledge-Based Systems

## Usage
### Tracking
1. Clone the code and unzip it in your computer.
2. Download imagenet-vgg-verydeep-16 and matconvnet, put them into TFCR folder. 
3. Prerequisites: Ubuntu 18, Matlab R2017a, GTX1080Ti, CUDA8.0.
4. Run the demo.m to test a tracking sequence using a default model.

## Results
| Dataste | OTB2013 | OTB2015 | TC128 | UAV123 |
| --------| --------| ------- | ------ | ----- | 
| Prec.   | 0.871   | 0.876   | 0.776  | 0.715 |
| AUC     | 0.671   | 0.665   | 0.564  | 0.512 | 


## Contact
Feedbacks and comments are welcome! Feel free to contact us via dyuanhit@gmail.com


## Acknowledgements
Some of the parameter settings and functions are borrowed from CREST(https://github.com/ybsong00/CREST-Release). 
