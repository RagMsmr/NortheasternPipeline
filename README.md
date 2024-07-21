# NortheasternPipeline
Pipeline Automation

Data Pipeline for Career Services Dashboard
This repository contains two main pipelines for processing and preparing data for the Career Services Dashboard:

Unified Pipeline
Event Automation Pipeline

Unified Pipeline
The Unified Pipeline processes data related to career services, advising appointments, and co-op placements.
Input Files:

Career Services Drop-in file
Career Advising appointments file
Co-op placement report file
Program and Co-op mapping files

Process:

Run the Unified_pipeline.ipynb Jupyter notebook
The code will transform and update the data in the input files

Output:
Updated versions of the input files, ready for dashboard integration


Event Automation Pipeline
The Event Automation Pipeline processes individual event data and maps it to a standardized format.
Input Files:

Individual event data files (e.g., Experience Expo info)
Mapping constants file
Seattle Campus Student data file

Process:

Run the Event_Automation_Pipeline.ipynb Jupyter notebook
The code will transform individual event data into a mapped format

Output:
Standardized event data ready for dashboard integration
How to Use

Ensure all required input files are downloaded from their respective sources and placed in the appropriate directories.
Run the corresponding Jupyter notebook for the pipeline you wish to execute.
The processed data will be output in a format suitable for feeding into the Career Services Dashboard.

Note: Make sure you have all necessary dependencies installed before running the notebooks.
This pipeline system allows for easy updating and maintenance of the Career Services Dashboard by automating the data processing and standardization steps.