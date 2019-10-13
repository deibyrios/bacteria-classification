# Q&A - Capstone Project - Bacteria classification


## MODEL

### In the [project description](https://github.com/deibyrios/bacteria-classification/blob/master/README.md) that we got, it is mentioned that _"a deep learning classifier has already been developed to classify colonies from two species, K. pneumoniae and E. coli, which could be extended for the more varied dataset"_. Can we have access to such previous work?
Ans:

## DATASET

### The Dataset contains 3 types of folders with 3 different types of images: Serial, Streak and Control. What is the meaning / purpose of each of those? 
Ans: The control is just one drop of bacteria-filled solution growing over time. The circular region is the space of how the initial drop. "Serial" has multiple drops but they are separate from each other so you can tell individual colonies apart. For "Streak", they are drawing lines across the petri dish with pipettes with different concentrations. More than one drop is used for "Streak".

### Images in 'Serial' folders are annotated with numbers 1-9. Do those numbers correspond to different bacterial species?
Ans:

### Deep Learning models need hundred thousands images or more to be successful. Are there only 200 images available for training?
Ans: Yes. They might be able to collect additional images but it is a time consuming process and will not get close to the scale needed to fully train deep learning models. We could consider using external/third party datasets if we can access them.

### Is there a different Dataset with images to test the model once final model in selected? If no, which type of images should we use for testing (type of images that will be used in a real life situation)?
Ans: No additional dataset as far as I know

### Folders in the Dataset are stamped with different times. Do images in the same type of folders (i.e. Serial) but with different timestamps, correspond to images of the the same bacterial colonies but taken at different times?
Ans: some of the colonies have pictures taken twice a day (every 12 hours) to document their growth.
 

## IMAGE pre-processing

### What type of images should we annotate (Serial, Streak, Control)? 
Ans:

### In our view, annotating the images will cause a DL model to learn from artificially modified images. At testing time, the model will then try to classify raw images (with no annotation) which will cause the model to fail. In past computer vision classification projects, we just use the name of the file to identify the class or put different classes in different folders. Could we fully understand why should we annotate the images?
Ans:
