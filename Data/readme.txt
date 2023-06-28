The dataset was crawled  from  Google (www.google.com) and Baidu (www.baidu.com) search engines, which was published from 《Logo-2K+:Discriminative Region Navigation and Augmentation Network for Scalable Logo Classiﬁcation》. The "Logo-2K+"consists of 2,341 classes and 167,140 images.

The “Logo-2K+” dataset consists of the following three parts:
(1) Logo-2K+.rar contains the original 167,140 logo images, which belong to 10 root-categories and 2,341 sub-classes.
(2) train_and_test.zip contains the training images and testing images used in our experiments.
(3) List.zip contains five txt files, they are: 
(a) Logo-2K+classes.txt contains the labels of all sub-classes; 
(b) train_images_root.txt contains the path of training images starting with the root-category; 
(c) test_images_root.txt contains the path of testing images starting with the root-category; 
(d) train_images.txt contains the relative pathname of training images starting with the sub-class; 
(e) test_images.txt contains the relative pathname of testing images starting with the sub-class.

In our experiments, we divide the original 167,140 logo images into training set and testing set, which are stored in the folder named “train_and_test”. When you train the model, you can use these well divided logo images directly, the relative pathnames of them are provided in the “train/test_images_root.txt” (the relative pathname starts with root-category) and “train/test_images.txt”(the relative pathname starts with sub-calss ) from the folder named “List”. Otherwise, you could choose the logo images from the original logo dataset, which are stored in the folder named “Logo-2K+ “.


