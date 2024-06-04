# Recipe Chatbot - built by Corey Swink

## Features
### Recipe suggestions based on input ingredients using AI
### High accuracy named entity recognition (NER)

## Dependencies
### BeautifulSoup
### pandas
### spaCy
### Doccano
### Pinecone
### Streamlit

# Installation and Setup

## go to [Pine](https://app.pinecone.io/) create a username and password, create an index with dimensions 786 and metric cosine, you will have to change the index name and server location with yours in the app.py.

## Clone the Repository
## First, clone the repository from GitHub:

### git clone https://github.com/csw1nk/Recipe_Chatbot.git
### in your terminal: go to repo 
```bash
cd Recipe_Chatbot/
```
### then
```bash
 touch .env
```
### add
```bash
PINECONE_API_KEY=[YOUR API KEY]
```
### then go to the repo: 
```bash
cd Project4/streamlit
```
## Install Dependencies
## To install the required dependencies, run:
```bash
pip install -r requirements.txt
```
## Load the data
## You will load the data into your pinecone index, run:
### (remember to change index name and location in file)
```bash
python Data_to_Pinecone.py
```
## Run the Application
## To start the Streamlit application, run:
### (remember to change index name and location in file)
```bash
streamlit run app.py
```
## Access the Application
## Open your web browser and go to:
```bash
http://localhost:8501
```
# Data Disclaimer
## The data used by this recipe chatbot comes from FoodNetwork.com and is intended for public use only. This project is not for commercial use and aims to drive traffic to FoodNetwork.com. We do not claim ownership of the recipes and do not intend to use them for monetary gain.

# Contact
## For help and feedback, feel free to contact the author at coreyswink0@gmail.com
