# Analysis of Job Postings and Skills dataset
Repo for analysing the job postings and skills dataset. 1. Preprocessing and preparing the model 2. Training the model 3. Analysis and reevaluation together with applying ML techniques

This repository will server for documenting all the steps and phases of using Machine Learning techniques and phases to analyse and retrive knowledge from the 2024 LinkedIn datasets of job postings and skills.
We will be analysing all the steps that we need to undergo for a better analysis and more aqurate and qualitative results.

What we aim from this analysis is to use the dataset to determine the most common job locations for data science roles and try to extract key information from job titles or summaries.  

The phases that we will implement to fully understand and derive conclusions is based on the quality of the dataset and the actions that would make sense more. 

# PHASE 1: Preparing the model

Based on this initial analysis we might need some preprocessing of the data so that we combine the data from separated datasets and also try to clean it. 

Starting with dataset anaysis:

Dataset contains of 3 different files and based on data we detect 3 data objects with their respective attributes.

1. Job Posting
2. Job Skill
3. Job Summary

Attributes of Job Posting object are:
    [
      'job_link',
      'last_processed_time',
      'last_status',
      'got_summary',
      'got_ner',
      'is_being_worked',
      'job_title',
      'company',
      'job_location',
      'first_seen',
      'search_city',
      'search_country',
      'search_position',
      'job_level',
      'job_type'
    ]

Attributes of Job Summary are:
    [
      'job_link',
      'job_summary'
    ]

Attributes of Job Skills are: 
    [
      'job_link',
      'job_skills'
    ]


