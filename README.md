# Using PySpark to Create a Recommendation System for Amazon products.
PySpark recommendation system for Amazon products created for INFO 607 at Drexel University.

## Project Overview:
The goal of our project was to create a recommendation system for Amazon user reviews on specific videos using PySpark. It was created as a final project for the class INFO 607: Applied Database Technologies at Drexel University. The data was downloaded from [here](https://jmcauley.ucsd.edu/data/amazon/).  We focused on the Amazon Instant Video subset to optimize computation time.

## File Manifest: 
`Folder /data` - Contains all relevant data for the project.
  - `ratings_Amazon_Instant_Video.csv` - Contains rating data for Amazon Instant Video products.
  - `video_names.csv` - Contains names of videos, found manually (More information in Jupyter Notebook).
- `ProductRecommender.ipynb` - Main Notebook for this project.

## Reason for Project
Recommendation systems are one of the go-to projects for learning how to work with PySpark and cloud computing.  Creating recommendation systems can allow a company to predict what a user will or will not like and improving their experience accordingly.

## Team Members:

Our team consisted of the following individuals (alphabetized by last name): 

- Zach Carlson, zc378@drexel.edu
- Aviv Faraj,   af3228@drexel.edu
- Katy Matulay, km3868@drexel.edu

## Project Requirements
Because of the size of the dataset and how long training takes, we recommend running this on a Windows computer using a local configuration.  See `ProductRecommender.ipynb` for more information.


## Python Requirements
- Python ≥ 3.8.
- Python libraries required:
  - matplotlib.pylot
  - pandas
  - pyspark

## How to Execute Notebook: 

All of the code in this project needs to be opened in a Jupyter notebook environment. We recommend using Google Colab.  See `ProductRecommender.ipynb` for more information.

## Known Limitations of Project:
- **Older dataset**.  The dataset contains ratings from 1999 to 2014.  Having a dataset that includes more current ratings would help more accurately predict ratings.  Additionally, in the last decade several genres have entered mainstream popularity such as LGBTQIA+ content, non-English speaking content, and limited series (e.g. Heartstopper, Squid Game, and Midnight Mass).  Having ratings data on these more recent types of content can help improve accurately as well.
- **Limited hardware**.  Training recomendation systems using Google Colab without paying for a premium account limits the size of data we can work with and the hyperparameters we test.  Having a cloud platform account or better hardware would help with computation time and allow us to test more values before selecting a best model.
