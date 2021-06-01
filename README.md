# PetFinder Pipeline

Course Project for CSCI 6502 - Big Data Analytics at CU Boulder

## Summary

**Data Pipeline**

- Build a batch driven application which ingests adoptable dog data in my area using the PetFinder API

- Pull in adoptable dogs every 4 hours using Azure Data Factory, and store data in Azure Data Lake Storage

**Sentiment Analysis**

- Understand the polarity and subjectivity sentiment scores for adoptable dogs based on their posting descriptions
- Compare sentiment analysis of different dog breeds for adoption

## Learn More

Read more about the project in the docs below:

- [Summary](./docs/Summary.md)
- [Developer Notes](./docs/DeveloperSettings.md)

## Repository Contents

Please see below for the high level repository organization

```bash
--- petfinderpipeline
|   --- adf-resources # azure data factory code for web and copy pipeline
|   --- data # datasets for analysis
|   --- docs # developer settings and evaluation documentation
|   --- jupyter # jupyter notebooks and analysis
|   --- myvenv # virtual environment files
```
