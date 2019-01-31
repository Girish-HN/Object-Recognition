# Object-Recognition

Steps to follow:

Step 0: Install Anaconda package from the official anaconda website https://www.anaconda.com/distribution/#download-section (Select Python 3.6)

Step 1: Create a conda environment by running the commands:
          "conda create -n <ENVIRONMENT NAME> python=3.6 anaconda"
          "activate <ENVIRONMENT NAME>"

Install the necessary packages

Step 2: Run the following code in cmd:
        "conda install tensorflow numpy scipy opencv pillow matplotlib h5py keras scikit-image "

Install the imageai library

Step 3: Run the following command in cmd:
        "pip install https://github.com/OlafenwaMoses/ImageAI/releases/download/2.0.2/imageai-2.0.2-py3-none-any.whl"
 OR
 
Alternative Step 3

Step 3: Navigate to the following page: https://github.com/OlafenwaMoses/ImageAI/releases
        
        Download the package "imageai-2.0.2-py3-none-any.whl"
        
        Navigate to the directory where the file is downloaded
        
        Run the following command "pip install imageai-2.0.2-py3-none-any.whl"

Step 4:Now download the pretrained model required to generate predictions. This model is based on RetinaNet https://github.com/OlafenwaMoses/ImageAI/releases/download/1.0/resnet50_coco_best_v2.0.1.h5

Step 5: Copy the downloaded file to current working directory

Step 6: Open jupyter notebook (type jupyter notebook in your terminal) and run the codes
