# About the UK Housing Prices (2015-2024) dataset
This dataset was sourced from Kaggle at the following [link](https://www.kaggle.com/datasets/swarupsudulaganti/uk-house-price-prediction-dataset-2015-to-2024).
All credit for sourcing and cleaning this dataset go to the user who provided the dataset. 
## Dataset Description:
This dataset has been meticulously pre-processed from the official UK government’s Price Paid Data, available for research purposes. The original dataset contains millions of rows spanning from 1995 to 2024, which posed significant challenges for machine learning operations due to its large size. For this project, we focused on house price predictions and filtered the data to only include transactions from 2015 to 2024. The final dataset contains 90,000 randomly sampled records, which should be ideal for training machine learning models efficiently.
The goal of this dataset is to provide a well-structured, pre-processed dataset for students, researchers, and developers interested in creating house price prediction models using UK data. There are limited UK house price datasets available on Kaggle, so this contribution aims to fill that gap, offering a reliable dataset for dissertations, academic projects, or research purposes.
This dataset is tailored for use in supervised learning models and has been cleaned, ensuring the removal of missing values and encoding of categorical variables. We hope this serves as a valuable resource for anyone studying house price prediction or real estate trends in the UK.

## Features:
**Feature Name** - **Description**

* **Price** - Sale price of the property (target variable).

* **Date** - Date of the property transaction. Converted to datetime format for easier handling.

* **Postcode** - Postcode of the property, offering location-based information.

* **property_type** - Type of property (Detached, Semi-detached, Terraced, Flat, etc.).

* **new_build** - Indicator whether the property was newly built at the time of sale (Yes or No).

* **freehold** - Indicator whether the property was sold as freehold or leasehold (Freehold, Leasehold).

* **Street** - Street name of the property location.
Locality - Locality of the property.

* **Town** - Town or city where the property is located.
District - Administrative district of the property.

* **County** - County where the property is located.

**File Information**:
The dataset is saved as a CSV file with 90,000 records, each representing a property transaction in the UK from 2015 to 2024.