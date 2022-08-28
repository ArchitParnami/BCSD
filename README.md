# BCSD: Bank Checks Segmentation Database

https://www.kaggle.com/datasets/saifkhichi96/bank-checks-signatures-segmentation-dataset

## About Dataset
This dataset consists of 158 images of bank checks, with segmentation masks for signatures on the checks. It was created to train a network for signature extraction from bank checks.

Images of bank checks were obtained from different sources (as listed), and resized such that the longer side of each image is 2240px with a resolution of 300px/in. All images were also converted to JPEG format. Segmentation masks for the signatures on these checks were manually created, and the dataset was divided into 129 training images (82%) and 29 test images (18%).

Most of the checks have one signature each, but there are a few with more than one signature per image. The 29 images in the test set were all taken from Google Image Search. These images were lower quality than the images in the test set, and were scaled up when resizing in the preprocessing step. Therefore, the test set is inherently more difficult to segment than the training set.
Citation

If you decide to use this dataset in your work, please include the following citation:  
~~~
Khan, Muhammad Saif Ullah. “A Novel Segmentation Dataset for Signatures on Bank Checks.” ArXiv:2104.12203 [Cs], Apr. 2021. arXiv.org, http://arxiv.org/abs/2104.12203.
~~~


## Acknowledgements
~~~
[1] P. Dansena, S. Bag, and R. Pal, “Differentiating Pen Inks in Hand-written Bank Cheques Using Multi-Layer Perceptron”, Proc. of 7th International Conference on Pattern recognition and Machine Intelligence, Kolkata, India, December 2017.
~~~