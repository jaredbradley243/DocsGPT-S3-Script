# DocsGPT - S3 Integration

## Overview
This project involves the integration of Amazon S3 for storing and retrieving documents, along with processing documents for efficient indexing in a vector space for similarity search and content-based retrieval.

## Key Features

### S3 Integration
- **Automated Interaction with S3**: The script can automatically download documents from a specified S3 bucket, process them, and upload the results back to S3.
- **Role-Based Access**: The script supports AWS role-based access, ensuring secure interaction with S3 services.

### Progress Tracking
- **Interactive Progress Bars**: Utilizes `tqdm` for displaying progress in both downloading from and uploading to S3, enhancing user experience.

## Technologies

- Python ![python-logo-only](https://github.com/jaredbradley243/DocsGPT-S3-Script/assets/107898107/c3d2ee19-fa5a-4374-931e-9f43e63935ea)

- Boto3 ![boto3](https://github.com/jaredbradley243/DocsGPT-S3-Script/assets/107898107/6f0e536b-4cfc-49f4-82cf-ab449264bd78)

- AWS S3 ![Amazon-S3-Logo](https://github.com/jaredbradley243/DocsGPT-S3-Script/assets/107898107/4ae6aa2e-6793-4cc4-8c88-7ed60db49f47)


### Tools:
- Git ![icons8-git](https://user-images.githubusercontent.com/107898107/211131596-fdb65679-35fb-4d60-8ca2-5ec536487391.svg)
- GitHub ![icons8-github](https://user-images.githubusercontent.com/107898107/211131605-60836c1f-9fe5-4567-a6f1-6afb2dfce9b6.svg)

## Summary

### What I Learned

1. **AWS S3 Integration**: Gained practical experience in integrating and automating interactions with AWS S3 using AWS' SDK for Python, Boto3.
2. **Python With Statement and Context Managers**: Gained experience using 'With Statements' in Python with a custom class behaving as a context manager. 

### What Could Be Improved
- **Handling Very Large Datasets**: Developing efficient ways to process and handle extrmely large datasets (in the millions) without overwhelming system resources. For example, iterating over Python generator rather than list to save memory.
