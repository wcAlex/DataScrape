# Jupyter notebook environment setup
	1. Go to notebook location (work folder) : ex: workspace/machine_learning/data_collection/DataScrape/image_collection
	2. Activate environment (create one if you don't have - conda create -n cs230 python=3.6 anaconda)
        conda activate jupyterbook
	3. Enable anaconda environment selection in jupyter notebook.
	      conda install -n notebook_env nb_conda_kernels
	4. Type `jupyter notebook`
	5. Open notebook at "http://localhost:8888" .
	6. Select the 'jupyterbook' anaconda environment ("jupyterbook" in this case)
  7. pip install google_images_download
  8. pip install opencv-python
  9. Download chromedriver from https://sites.google.com/a/chromium.org/chromedriver/downloads, google_images_download library need to install ‘selenium’ library along with ‘chromedriver’ extension if you would want to download more than 100 images per keyword. The good part is Selenium would have automatically installed at step 7 during pip install, we only need to install the chrome driver here. For more details, please check this link: https://google-images-download.readthedocs.io/en/latest/troubleshooting.html#installing-the-chromedriver-with-selenium
  
# Tools
GoogleImageDownload.ipynb : download images from google search, process images with opencv.
