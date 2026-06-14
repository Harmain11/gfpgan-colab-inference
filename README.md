# GFPGAN Colab Inference  

## Overview  
This notebook demonstrates how to run GFPGAN for face restoration on low-quality or degraded images using Google Colab. It automates cloning the GFPGAN repository, installing required dependencies, uploading images, restoring faces with enhanced backgrounds, and visualizing results side-by-side. Additionally, it includes a simple Flask app for serving the restoration model via an API endpoint.  

## Features  
- Clones and sets up GFPGAN environment automatically in Colab.  
- Upload your own images for restoration.  
- Performs face restoration and background enhancement using Real-ESRGAN.  
- Visualizes input versus restored images for both cropped faces and whole images.  
- Provides downloadable results as a zip file.  
- Flask server setup for image restoration API.  

## Tech Stack  
- Python  
- Jupyter Notebook / Google Colab  
- Flask for serving a REST API  
- GFPGAN, BasicSR, FaceXLib, Real-ESRGAN libraries for face restoration and super-resolution  

## How to Use  
1. Open the notebook in Google Colab.  
2. Run each cell sequentially to install dependencies and clone GFPGAN.  
3. Upload your images when prompted.  
4. Run the inference cell to restore images.  
5. View side-by-side comparisons of original and restored images.  
6. Download the results if needed.  
7. Optionally, run the Flask server cell to serve restoration via API.  

## Status  
This notebook is well-organized and prepared for presentation and usage on GitHub, providing a smooth experience replicating GFPGAN restoration workflows in Colab.