# 👁️ Week 1: Seeing the World Through Numbers
## Understanding Computer Vision and the Nature of Images
Welcome to Week 1! This week, we go back to the roots—not of magic or AI hype, but to the fundamentals of how machines interpret the world visually.

The science of enabling machines to **comprehend visual input**, such as pictures and videos, so they can interpret what they "see," is known as ***computer vision***. However, in order to understand this, we must first address two fundamental questions:
## 📷 What is Computer Vision?
**Computer vision** means the extraction of information from images, text, videos, etc. Sometimes computer vision tries to mimic human vision. It’s a subset of computer-based intelligence or Artificial intelligence which collects information from digital images or videos and analyze them to define the attributes. This could mean recognizing objects, detecting motion, analyzing facial expressions, or identifying defects in a manufacturing line.  
The entire process involves image acquiring, screening, analyzing, identifying, and extracting information. This extensive processing helps computers to understand any visual content and act on it accordingly.  Computer vision projects translate digital visual content into precise descriptions to gather multi-dimensional data. This data is then turned into a computer-readable language to aid the decision-making process. The main objective of this branch of Artificial intelligence is to teach machines to collect information from images. 

The goal is **not just to store or display images**, but to interpret them—turning raw pixels into actionable data.

Think of it like this:
* Humans look at an image and instantly understand its context.
* Machines see a **matrix of pixel values**—and that’s it.

Computer vision is the bridge between those two ways of seeing.
### Application of Computer Vision
* **Medical Imaging**: Computer vision helps in MRI reconstruction, automatic pathology, diagnosis, and computer aided surgeries and more.
* **AR/VR**: Object occlusion, outside-in tracking, and inside-out tracking for virtual and augmented reality.
* **Smartphones**: All the photo filters (including animation filters on social media), QR code scanners, panorama construction, Computational photography, face detectors, image detectors like (Google Lens, Night Sight) that we use are computer vision applications.
* **Internet**: Image search,  Mapping, photo captioning, Ariel imaging for maps, video categorization and more
  
[Applications of Computer Vision](https://www.geeksforgeeks.org/applications-of-computer-vision/)

## 🧮 What is an Image (to a Machine)?
An image, for a computer, is a grid (or matrix) of pixels. Each pixel represents a color value. In a color image:
* Each pixel has 3 values (called as **channels**): Red, Green, Blue (RGB).
* These values range from 0 to 255.

So, for a 100x100 image:
* There are 10,000 pixels.
* Each pixel has 3 color channels.
*That’s 30,000 numbers.

**Grayscale images?** Just one number per pixel. Black is 0, white is 255, and everything in between is a shade of gray.

The image you're viewing right now on your screen is really just numbers stored in a file format like .png or .jpg, decoded and rendered to look like what your brain would expect.  

For a machine, there’s no racoon. Just [34, 76, 123], repeated thousands or millions of times.  

[What is a Digital Image](https://www.geeksforgeeks.org/what-do-you-mean-by-digital-image/): Go through the material till Technical aspects of digital Images (inclusive).
## 📝 Content for this Week
Our objective this week is simple: **understand how images work at the pixel level**, and learn how to work with them using code.  
### Installation of Jupyter Notebook on your machine (follow any one of them)
1. [install Jupyter Notebook for Windows](https://www.youtube.com/watch?v=HLD-Ll_-IT4)
2. [Setting up Conda environment with Jupyter Notebook ](https://www.youtube.com/watch?v=WUeBzT43JyY)  
3. [Getting Started with Jupyter Notebooks in VS Code ](https://www.youtube.com/watch?v=suAkMeWJ1yE)
4. [Installation of Jupyter Notebook in MacOS](https://www.youtube.com/watch?v=pkjtbnsX7Yw)
5. [Installation of Jupyter Notebook on Linux](https://www.youtube.com/watch?v=dFIlItQ137c)
### Getting familiar with Jupyter Notebook
[Jupyter Notebook Tutorial](https://www.youtube.com/watch?v=5pf0_bpNbkw)
### OpenCV 
OpenCV (Open Source Computer Vision), a cross-platform and free to use library of functions is based on real-time Computer Vision which supports Deep Learning frameworks that aids in image and video processing. In Computer Vision, the principal element is to extract the pixels from the image to study the objects and thus understand what it contains. Below are a few key aspects that Computer Vision seeks to recognize in the photographs:

* **Object Detection**: The location of the object.
* **Object Recognition**: The objects in the image, and their positions.
* **Object Classification**: The broad category that the object lies in.
* **Object Segmentation**: The pixels belonging to that object.
  
To have this library make sure the latest version python and pip (python package installer) is already installed on your device.  
  
To install OpenCV, just go to the command-line and type the following commands:
1. On Windows/MacOS: **pip install opencv-python**
2. On Linux: **pip3 install opencv-python**
3. [Set up Opencv with anaconda environment](https://www.geeksforgeeks.org/set-opencv-anaconda-environment/)

#### Getting started With OpenCV
1. [Working With Images- Let's get started 😌](https://www.geeksforgeeks.org/reading-image-opencv-using-python/)
2. [Image Processing](https://www.geeksforgeeks.org/opencv-python-tutorial/#-22-image-processing): Till Grayscaling of images
