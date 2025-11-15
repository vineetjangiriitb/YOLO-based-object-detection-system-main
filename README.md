Object detection model with YOLO for identifying components of a humanoid robot
It took a lot of eﬀorts to get the dataset for this model and to make annotations for the images in
the dataset and it took intense eﬀorts to keep the dataset accurate while also keeping it large
enough to fine tune model properly. In this, no dataset was available so I created my own dataset
using google images and labelling them on labelme. In this, I was initially getting low accuracy in
model due to very small dataset size for fine tuning. But, using data augmentation, I was able to
get through the problem.
All the test performances as well as prediction images are attached in code and folder alongith
various visualisation curves like Confusion matrix, P_curve, R_curve etc.
Also please download the Code.ipynb file in your computer to access its code
