Computer Vision
================================================================

We all have witnessed an accelerated research in the field of Computer vision. Major contributions started in the year of 2012, CNNs started to rule
and ofcourse compute was on parallel made accesible & affordable.

Image & Video tasks
---------------------

* **Object Detection :**
    Goal is to detect some predefined objects in an image and put bounding boxes on them (as output image).
    Its has numerous use cases, popularly : Self driving cars to detect various objects on road, in Sports to track objects (eg. ball, player),
    image search, counting the objects like entities in a shopping store or counting visitors or manage crowd.

* **Image Segmentation :**
    Divides image into segments where each pixel in image is mapped to some object.
    Used in autonomous vehicle to segment roads, editing apps to remove/blur background, medical imaging to segment out anomalies.

* **Depth Estimation :**
    Predicts the depths as gradients on Image. Used to get 3D representations from 2D Images and volumetric estimatations from object images.

* **Image to Image :**
    Where input and output both are images, used in image super resolutions, image style transfers, image inpainting where we remove/add
    objects from images, image colorization where we convert black & white images to RGB, etc.

* **Image to Text :**
    Used in image captioning to describe images in text, Optical character recognition, etc. 

Coding Notebooks
--------------------

.. nbgallery::

  ../notebooks/4_CV_ObjectDetection.ipynb
  ../notebooks/4_CV_SegmentationAndDepthEstimation.ipynb