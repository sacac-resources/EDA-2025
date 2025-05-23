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
The data used during the workshop is not hosted on GitHub. The data is available on the SACAC Google Drive folder [here](https://drive.google.com/drive/folders/1YcMv9eZFhopJvv1TjTTH029e5ufIw8c_?usp=drive_link) and you may download it if you prefer. However, the workshop examples will use `pandas` to load the data directly from the Google Drive folder. A dictionary is created in the beginning of each example listing the required URLs. No further setup is required from your side - if the `test_setup` notebook runs correctly, then the data is ready for use.

The data is originally from the Kaggle challenge: https://www.kaggle.com/datasets/edumagalhaes/quality-prediction-in-a-mining-process.
The dataset has been modified to correct faulty timestamp and rename columns.

_______________________________________________________________________
## Attendance on the day
_Venue for in person attendees:_
Room C229/230, Department of Chemical Engineering, Stellenbosch University

_Link for online attendees:_
[Teams link](https://teams.microsoft.com/l/meetup-join/19%3ameeting_Nzg1N2RlZmQtYmMzMC00NGE5LWFmNjctNDQ3ZTAwNTQxYTc4%40thread.v2/0?context=%7b%22Tid%22%3a%22a6fa3b03-0a3c-4258-8433-a120dffcd348%22%2c%22Oid%22%3a%226d166535-09ed-44dc-a121-8bcc07886777%22%7d)

## Agenda
| Time          | Activity|
| :---          | :--- |
| 8.30 - 9.00   | Coffee and tea for in person attendees |
| 9.00 - 9.30   | Workshop introduction, assist with setup as necessary |
| 9.30 - 10.30  | *Topic 1*: The nature of data and pre-processing |
| 10.30 - 10.45 | Break |
| 10.45 - 12.15 | *Topic 2*: Dimensionality reduction and data visualisation |
| 12.15 - 12.45 | Lunch break |
| 12.45 - 14.15 | *Topic 3*: Clustering |
| 14.15 - 14.30 | Break |
| 14.30 - 16.00 | *Topic 4*: Model interpretation and wrap-up |

## Topics covered during the workshop
### Nature of data / Pre-processing / Time series
* Context of process data analysis (CRISP-DM, process monitoring)
* Process data - origins and ingest
* Challenging process data characteristis
* Data visualization
* Data cleaning (removal, smoothing, replacement, downsampling)
* Moving averages, exponential moving average


Data ingest: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sacac-resources/EDA-2025/blob/main/examples/data_ingest.ipynb)

Data visualisation: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sacac-resources/EDA-2025/blob/main/examples/data_visualization.ipynb)

Data cleaning: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sacac-resources/EDA-2025/blob/main/examples/data_cleaning.ipynb)


### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sacac-resources/EDA-2025/blob/main/examples/dimensionality_reduction.ipynb) Dimensionality reduction 
*	Principal component analysis
*	Manifold learning and UMAP
*	Autoencoders (bonus content)

Bonus content: autoencoders [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sacac-resources/EDA-2025/blob/main/examples/autoencoders.ipynb)




### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sacac-resources/EDA-2025/blob/main/examples/clustering.ipynb) Clustering
*	K-means clustering
*	DBSCAN
*	Interpreting clustering

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sacac-resources/EDA-2025/blob/main/examples/model_interpretation.ipynb) Model interpretation (w/ tree-based methods)
*	Decision tree introduction
*	Variable importance and partial dependence
*	SHAP analysis (bonus content)
