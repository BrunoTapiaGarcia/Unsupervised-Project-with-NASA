# Predictive Analysis of Hurricane Maria's Impact (Team Project)

**Objective**

The primary objective of this project was to analyze and predict the environmental impact of Hurricane Maria using Sentinel-2 satellite data provided by NASA. By employing advanced image analysis and machine learning techniques, we aimed to identify the regions most affected by the hurricane and build predictive models to enhance disaster response strategies.

**Datasets**

Sentinel-2 Satellite Data: Pre- and post-event images of the areas affected by Hurricane Maria.
Labeled Data: Images labeled with environmental features for training the models.

**Model Types Used**

YOLO (You Only Look Once) Model: A state-of-the-art object detection model used to identify and label features in satellite images, allowing for accurate detection of affected regions.
NDVI (Normalized Difference Vegetation Index) Analysis: Used to assess the health of vegetation before and after the hurricane, providing a clear picture of the environmental impact.
Image Labeling and Object Detection: Techniques to prepare the satellite images for further modeling and analysis.

**Modeling Steps**

Package and Dataset Imports:
Import relevant libraries for image processing and machine learning, and load the Sentinel-2 data.

Exploratory Data Analysis (EDA) and Data Preprocessing (DP):
EDA: Conducted a detailed analysis of satellite data to identify patterns and correlations.
DP: Processed images to enhance features, labeled data for model training, and prepared datasets for analysis.

Model Development and Evaluation:
Developed YOLO models and applied NDVI analysis to assess the hurricane's impact. Evaluated model performance using accuracy metrics and visual inspections.

Hyperparameter Tuning:
Optimized YOLO model parameters to improve detection accuracy and minimize false positives.

Final Model Selection:
Selected the best-performing YOLO model based on precision, recall, and overall accuracy. Used this model for final predictions and analysis of the hurricane’s impact.

**My contributions:**

Image Labeling: Labeled over 25 pre- and post-event images to prepare them for modeling.

Analysis and Code: Assisted in developing and documenting the analysis, ensuring clear and concise explanations of the steps taken.

Model Development: Contributed to building a Yolo model using 50 epochs to detect objects in the satellite images.



<a href="A1_Team2_Chuys_Latino_Group.ipynb">Download the Jupyter file</a> 

<a href="A1_Team2_Chuys_Latino_Group.html">View project in HTML</a>
