<p align="center">
  <a href="https://www.perceptilabs.com">
  <img src="./pl_logo.png">
  </a>
</p>

# Brain Tumor Dataset
This dataset<sup>1</sup> contains 232x300-pixel images of brain image scans.

The data can be used to build and train an ML model that can detect brain tumors. 

# Structure
This repo has the following structure:
* **/data**: contains the images of brain scans. The **yes** subdirectory contains brain scan images with tumors, and the **no** subdirectory contains brain scan images without tumors. The following is an example image from the respective folders:

![](/data/yes/Y1.jpg)  |  ![](/data/no/N20.JPG)

* **/data/data.csv**: CSV file that maps the images to "yes" and "no" labels for use in loading the data into PerceptiLabs. "yes" means the image contains a brain tumor, and "no" means the image doesn't contain a brain tumor.

The following shows a partial example of the data stored in the CSV file:

| images | labels |
| ---------- | ------ |
| yes/Y38.jpg | yes |
| no/no 3.jpg | no |

# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection
