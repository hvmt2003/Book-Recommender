# End-to-End-Book-Recommender-System

## Workflow

- config.yaml
- entity
- config/configuration.py
- components
- pipeline
- main.py
- app.py


# How to run?
### STEPS:

Clone the repository


### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n books python=3.7.10 -y
```

```bash
conda activate books
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


Now run,
```bash
streamlit run app.py
```


# Streamlit app Docker Image Deployment

## 1. Login with your AWS console and launch an EC2 instance
## 2. Run the following commands

Note: Do the port mapping to this port:- 8501

```bash
sudo apt-get update -y

sudo apt-get upgrade

