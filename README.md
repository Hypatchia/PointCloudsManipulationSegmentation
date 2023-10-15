# PointCloudsManipulationSegmentation
Welcome to my PointClouds Filtering and Segmentation repository! This repository contains two projects aimed at processing and analyzing point clouds, which are essential in various fields such as computer vision, robotics, and environmental scanning.

## Built with:
   [![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python)](https://www.python.org/)[![Open3D](https://img.shields.io/badge/Open3D-0.13%2B-blue?style=flat&logo=open3d)](http://www.open3d.org/)
    [![Scikit-learn (sklearn)](https://img.shields.io/badge/Scikit--learn-0.24%2B-yellow?style=flat&logo=scikit-learn)](https://scikit-learn.org/stable/) [![NumPy](https://img.shields.io/badge/NumPy-1.20%2B-yellow?style=flat&logo=numpy)](https://numpy.org/) [![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4%2B-yellow?style=flat&logo=matplotlib)](https://matplotlib.org/)

## PointCloudsFiltering.ipynb:
The PointClouds Filtering project by is designed to provide a set of tools and algorithms for filtering and cleaning point cloud data. 
Point clouds are often noisy or contain outliers, making it challenging to work with them effectively.
* For a better view of the pr
**Features**
* Noise Reduction: Remove noise from point cloud data to improve the quality and accuracy of subsequent processing steps.
* Outlier Detection: Identify and remove outlier points that do not belong to the main structure of the point cloud.
* Downsampling: Reduce the point cloud density while preserving critical information, making it more manageable.
**Getting Started**
To get started with the PointClouds Filtering project, please refer to the project-specific notebook for detailed instructions on how to set up and use the filtering tools.
## PointCloudsSegmentation.ipynb:

The PointClouds Segmentation project focuses on segmenting point clouds into meaningful parts or objects. Segmentation is crucial for various applications, such as object recognition, scene understanding, and autonomous navigation, as it allows you to extract valuable information from a point cloud dataset.

**Features**
* Object Detection: Identify and separate individual objects within the point cloud for object recognition tasks.
* Color-Based Segmentation: Utilize color information to segment point clouds based on object color.

**Run Code:**

* Clone Repository
* Download ShapenNet Dataset using the provided script

    ~~~
    python download_dataset.py
    ~~~
* Install dependencies
* Use Run the notebook preferably in google colab by changing resource to T4 GPU.
