## <center> Accurate Estimation of Body Height from a Single Depth Image &#8195; via a Four-Stage Developing Network </center>

![Image of liuchengtu](https://depth2height.github.io/images/1.jpg)
### Introduction
&#8195; We use a Kinect camera to create a human body dataset with 2136 RGB-D images which consists of 10 postures, including upright, walking, sitting, bending, arms raising slightly, unrolling arms, arms over head, waving hands, clapping and having a waistline. There are 14 volunteers in our dataset. They can stand anywhere with arbitrary clothes. Their heights ranges from 158cm to 184cm, which covers a wide range of height. The following figure shows some examples:
![Image of shili](https://depth2height.github.io/images/2.jpg)
##### Composition and division of our data set
![Image of division](https://depth2height.github.io/images/3.jpg)
&#8195; Our entire dataset is divided into three parts: part A, B and C. Part A is the training set with 1707 images. partB and C together forms the test set with totally 429 images.   
&#8195;We ﬁrst divide 1767 images from 12 people  into two parts: part A and B . Part A has 1707 images to form the training set. PartB, denoted as Familiar-test, has 60 images and is part of the test set. Network may recognize the identity information from the image of Part B.  
&#8195;The 369 images of all the other volunteers are part C, denoted as Strange-test. It is impossible for network to recognize any identity information from part C since none of them appears in the training set. It will be very easy to determine whether the network has learned identity information or body height under such a data set conﬁguration. It only need to compare the difference of accuracy between part B and C.
### Cite
If you use the dataset or code, please cite the following work:  
```
@inproceedings{deep2height2020,  
  title={Accurate Estimation of Body Height from a Single Depth Image via a Four-Stage Developing Network},  
  author={Fukun Yin and Shizhe Zhou},  
  booktitle={IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},  
  year={2020}  
}  
```

## We will publish data set and code after the coronavirus is over.
