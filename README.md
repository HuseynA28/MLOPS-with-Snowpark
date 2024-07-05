# Snowflake MLOPS Project.

## Introduction

Welcome to the Snowflake MLOPS Project repository. This project demonstrates a complete MLOPS workflow using Snowflake, which includes data loading, preprocessing, model training, and inference. The goal is to fully leverage Snowflake's capabilities to streamline machine learning pipelines in the cloud.

## Project Structure

- **.github/workflows/**: Contains GitHub Actions for CI/CD.
- **Notebooks/**: Jupyter notebooks that detail each step of the ML process.
  - `1_load_data.ipynb`: Data ingestion into Snowflake.
  - `feature_engineering.ipynb`: Data cleaning and transformation.
  - `train_save_model.ipynb`: Model training and serialization.
- **dataset/**: Sample dataset used for training.
  - `advertising.csv`: Advertising data with metrics like TV, radio, and newspaper spend.
- **Dockerfile**: Defines the Docker environment for the project.
- **docker-compose.yml**: Manages the Docker services.
- **requirements.txt**: Lists all dependencies required for the project.

## Features

- **Data Loading**: Automated scripts to load data directly into Snowflake using Snowpark.
- **Feature Engineering**: Transformation scripts to prepare data for modeling.
- **Model Training**: Utilization of Snowflake's in-database capabilities to train models.
- **Inference**: Deployment of a user-defined function (UDF) in Snowflake for real-time predictions.

## Getting Started

### Prerequisites

- Docker installed on your machine.
- Access to a Snowflake account.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/snowflake-mlops.git
   cd snowflake-mlops
