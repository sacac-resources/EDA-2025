# SACAC Exploratory Data Analysis workshop
Repository to host the SACAC Exploratory Data Analysis workshop files (23 May 2025)

## Setup

### Cloning the repository to your Google Drive
The workshop will include multiple hands-on examples, and participants will have the opportunity to get to know the various EDA tools available. We will rely on the Python programming language, implemented in [Google Colab](https://colab.google/) which requires no setup and provides access to compute resources.

To take part in the workshop, you will need to clone this GitHub repository (repo) into your own personal Google Drive.

The `clone-repo` file will guide you through the process of cloning the repo to your own Google Drive. You can open the `clone-repo` file directly by clicking on the "Open in Colab" button below. Note that this will navigate you to the Google Colab site, so you may want to open in a new tab. You will need to provide permission for the repository to be cloned to your Google Drive. If you prefer, you may simply download the repository as a zip-file and upload it to your Google Drive manually.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sacac-resources/EDA-2025/blob/main/clone-repo.ipynb)

### Checking your setup in Google Colab
After you have cloned the repo to your Google Drive, we suggest you run the `test-setup` notebook to make sure everything is running correctly. 
1. Go to your [Google Drive](https://drive.google.com/) and navigate to the EDA-2025 folder you've just cloned.
2. Go to `/examples` and open the `test_setup` notebook
3. Make sure to edit the path in the first cell of the notebook, as explained in the instructions.
4. You should be able to run all cells in the notebook

### Data used during the EDA workshop
The data used during the workshop is not hosted on GitHub. The data is available on the SACAC Google Drive folder [here](https://drive.google.com/drive/folders/1YcMv9eZFhopJvv1TjTTH029e5ufIw8c_?usp=drive_link) and you may download it if you prefer. However, the workshop examples will use `pandas` to load the data directly from the Google Drive folder. A dictionary is created in the beginning of each sample listing the required URLs. No further setup is required from your side - if the `test_setup` notebook runs correctly, then the data is ready for use.

_______________________________________________________________________

## Topics covered during the workshop
### Nature of data / Pre-processing / Time series
* Context of process data analysis (CRISP-DM, process monitoring)
* Process data - origins and ingest
* Challenging process data characteristis
* Data visualization
* Data cleaning (removal, smoothing, replacement, downsampling)
* Moving averages, exponential moving average

### Dimensionality reduction
*	Principal component analysis
*	Manifold learning and UMAP
*	Autoencoders (bonus content)

### Clustering
*	K-means clustering
*	DBSCAN
*	Interpreting clustering

### Model interpretation (w/ tree-based methods)
*	Decision tree introduction
*	Variable importance and partial dependence
*	SHAP analysis (bonus content)
