# LITERATURE REVIEW

1.	Special Emphasis on Breakthrough in Computer Vision
  a.	Object Detection
    i.	CNNs (AlexNet_{1}, ImageNet_{2}, ResNet_{3})
  b.	Image Segmentation
    i.	RCNN_{4}
    ii.	U-Net_{5}
2.	Medical Imaging and Computer Vision
  a.	Chest Image – CheXNet_{6}, DenseNet_{7}
  b.	Diabetic Retinopathy_{8}
  c.	Skin Lesions_{9}
3.	Previous approaches to Bacterial Classification
  a.	Neural Network – Bacterial Colony Classification_{10}
  b.	Deep learning - Bacterial Colony Classification_{11}
  c.	Bacterial Image Segmentation_{12}

## 1
### 1a
Last decade has seen remarkable developments in the field of building image classifiers using computer vision.  The era of deep learning started with the success of AlexNet1 on the benchmark computer vision dataset, Imagenet (Russakovsky et al., 2019)2 focused on studying natural world images. This result was steadily followed by development large and deeper neural network architectures in the following years. These architectures saw remarkable improvement in model performance in contrast to any other traditional methods that included hand crafting features in literature. By 2015, models like ResNet (He et al., 2019)3 were performing better than a human baseline. This motivated researchers to make similar progress on even difficult tasks such as image segmentation.

### 1b
Biggest breakthrough of computer vision algorithms for image segmentation came in the form of U-Net which designed for solving the challenge of Cell tracking. The advantage of the method stemmed from its ability to learn from limited training data making it all the more effective for a wide variety of biomedical tasks.

## 2
The problem of using automated computer vision algorithms for the purposes of improving diagnosis from medical images is not a new phenomenon. Researchers have long been interested in applying the latest advancements in machine learning to improve the accuracy of their diagnostic procedures and achieve quick and reliable results.  

### 2a
Rajpurkar et al.6, used a modified version of state-of-the-art DenseNet (Huang et al., 2019)7
algorithm for exceeding human level performance on the task of detecting pneumonia by looking chest X-ray images. By visualizing the internal layers of the network, researchers were able to understand which the portion of images were responsible behind activation of the classifier. 

### 2b
Another example for using medical image to improve diagnosis comes studying detecting diabetic retinopathy from retina scans. 

### 2c 
In a recent paper from a collaboration between researchers at Google and dermatologists9, a model was developed that employs using Convolutional Neural Networks as image feature extractors and combining them with the other available information from patient’s medical history to predict the existence of a certain skin condition. This hybrid approach is designed to utilize the available metadata along with raw images to incorporate more information while building our classifier.

### 3a

### 3b

### 3c

# References

[1] Krizhevsky, A., Sutskever, I. and Hinton, G. (2019). ImageNet Classification with Deep Convolutional Neural Networks. [online] Papers.nips.cc. Available at: https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks [Accessed 16 Oct. 2019].
[2] Russakovsky, O., Deng, J., Su, H., Krause, J., Satheesh, S., Ma, S., Huang, Z., Karpathy, A., Khosla, A., Bernstein, M., Berg, A. and Fei-Fei, L. (2019). ImageNet Large Scale Visual Recognition Challenge. [online] arXiv.org. Available at: https://arxiv.org/abs/1409.0575 [Accessed 16 Oct. 2019]
[3] He, K., Zhang, X., Ren, S. and Sun, J. (2019). Deep Residual Learning for Image Recognition. [online] arXiv.org. Available at: https://arxiv.org/abs/1512.03385 [Accessed 16 Oct. 2019].
[4] Girshick, R., Donahue, J., Darrell, T. and Malik, J. (2019). Rich feature hierarchies for accurate object detection and semantic segmentation. [online] arXiv.org. Available at: https://arxiv.org/abs/1311.2524 [Accessed 16 Oct. 2019].
[5] Ronneberger, O., Fischer, P. and Brox, T. (2019). U-Net: Convolutional Networks for Biomedical Image Segmentation. [online] arXiv.org. Available at: https://arxiv.org/abs/1505.04597 [Accessed 16 Oct. 2019].
[6] Rajpurkar, P., Irvin, J., Zhu, K., Yang, B., Mehta, H., Duan, T., Ding, D., Bagul, A., Langlotz, C., Shpanskaya, K., Lungren, M. and Ng, A. (2019). CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays with Deep Learning. [online] arXiv.org. Available at: https://arxiv.org/abs/1711.05225 [Accessed 16 Oct. 2019].
[7] Huang, G., Liu, Z., van der Maaten, L. and Weinberger, K. (2019). Densely Connected Convolutional Networks. [online] arXiv.org. Available at: https://arxiv.org/abs/1608.06993 [Accessed 16 Oct. 2019].
[8] Sayres, Rory et al., Using a Deep Learning Algorithm and Integrated Gradients Explanation to Assist Grading for Diabetic Retinopathy, Ophthalmology, Volume 126, Issue 4, 552 – 564
[9] Liu, Y., Jain, A., Eng, C., Way, D., Lee, K., Bui, P., Kanada, K., Marinho, G., Gallegos, J., Gabriele, S., Gupta, V., Singh, N., Natarajan, V., Hofmann-Wellenhof, R., Corrado, G., Peng, L., Webster, D., Ai, D., Huang, S., Liu, Y., Dunn, R. and Coz, D. (2019). A deep learning system for differential diagnosis of skin diseases. [online] arXiv.org. Available at: https://arxiv.org/abs/1909.05382 [Accessed 16 Oct. 2019].
[10] https://doi.org/10.1186/s12976-018-0093-x
[11] https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0184554 
[12] Dong Nie, Elizabeth A. Shank, and Vladimir Jojic. 2015. A deep framework for bacterial image segmentation and classification. In Proceedings of the 6th ACM Conference on Bioinformatics, Computational Biology and Health Informatics (BCB '15). ACM, New York, NY, USA, 306-314. DOI: http://dx.doi.org/10.1145/2808719.2808751 
