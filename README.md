# MA Thesis Repository – MACSS Program, University of Chicago

This repository contains the code and data associated with the MA thesis submitted to the Master of Arts in Computational Social Science (MACSS) program at the University of Chicago.

## Code Folder

- `BERT.ipynb`  
  Fine-tuned BERT model used for sentiment analysis on Google business reviews.

- `Dynamics_Topics_Modeling.ipynb`  
  Dynamic BERTopic model used to capture topic evolution across time from park-related reviews.

- `pspnet.ipynb`  
  PSPNet-based semantic segmentation model applied to Google Street View images to extract environmental features.

## Data Folder

- `aggregated_park_reviews_first_1000.csv`  
  Aggregated results from the first 1000 Google business reviews, including sentiment and topic labels. Raw review text is omitted for privacy.

- `parks_POI.csv`  
  Geolocation and visitation data for green spaces with complete data coverage (reviews, street views, and SVI index).

- `street_view_result_first_1000.csv`  
  First 1000 processed results from semantic analysis of street view imagery for green space entrances.

- `SVI_Socioeconomic.csv`  
  County-level Social Vulnerability Index (SVI) scores for socioeconomic analysis