# Data Collection and Production - EPPS 6302

## Course Overview

This course, taught by Dr. Karl Ho at The University of Texas at Dallas, introduces the theory, practices, and issues of data collection and production. Topics covered include data methods, data management, big data trends, and preparing data for modeling and reporting.

## Final Project

### Network Structure of the Digital Advertising Marketplace

**Description:** Analyzed the structure of digital advertising networks using network analysis techniques. The study involved collecting, cleaning, and analyzing data from various digital advertising platforms to understand the relationships and interactions within the digital advertising ecosystem.

### Main Components

#### Data Collection and Cleaning
- **Data Sources:** Collected data from various digital advertising platforms (News media from every state in the United States).
- **Data Cleaning:** Performed data cleaning and preprocessing to ensure data quality.

#### Network Analysis
- **Entity Relationships:** Analyzed relationships between entities within the digital advertising ecosystem.
- **Network Metrics:** Calculated network metrics to identify key entities and their roles.

#### Visualization
- **Network Diagram:** Visual representation of the digital advertising network structure.
- **Interaction Map:** Map showing interactions between different entities.

## Learning Objectives:
- Understand data theory and methods
- Develop instruments and schemes for data collection
- Manage and prepare data for analysis

## Instructions on how to use this repo

If you are interested in replicating the Neo4j database we explained in our report, upload this [`admapper.dump`](https://drive.google.com/file/d/1JpYsUGDlpQP3Dvq--1P46Km03weGfIxF/view?usp=share_link) into a Neo4j database locally (or AuraDB instance on the cloud). One can also build the Neo4j database from scratch, by replicating the data model shown in the report using the `.csv` files provided in the `neo4j_files` directory.

If you are interested in running the codebase on your own, use the `requirements.txt` file provided here to set up your environment with all the necessary packages. To understand this code base, please read the Jupyter notebooks (`.ipynb` files) in this order - `00_data_cleaning.ipynb`, `01_create_adjacency_list.ipynb`, and `02_analysis.ipynb`. We have added useful comments within the notebooks to ease the reading process. The point of the `.py` files in the codebase will become clear as one reads the notebook files. But the basic idea is that, whenever we had to run a multithreaded operation, due to issues with Jupyter notebooks on supporting such operations, we had to write up a `.py` script.
