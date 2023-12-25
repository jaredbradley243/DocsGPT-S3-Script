# DocsGPT - S3 Integration

## Overview
This project involves the integration of Amazon S3 for storing and retrieving documents, along with processing documents for efficient indexing in a vector space for similarity search and content-based retrieval. The script, written in Python, automates the ingestion of documents from either local directories or an S3 bucket, processes them, and subsequently uploads processed data back to S3.

## Key Features

### S3 Integration
- **Automated Interaction with S3**: The script can automatically download documents from a specified S3 bucket, process them, and upload the results back to S3.
- **Role-Based Access**: The script supports AWS role-based access, ensuring secure interaction with S3 services.

### Progress Tracking
- **Interactive Progress Bars**: Utilizes `tqdm` for displaying progress in both downloading from and uploading to S3, enhancing user experience.

## Technologies

- Python
- Boto3 
- AWS S3

### Tools:
- Git ![icons8-git](https://user-images.githubusercontent.com/107898107/211131596-fdb65679-35fb-4d60-8ca2-5ec536487391.svg)
- GitHub ![icons8-github](https://user-images.githubusercontent.com/107898107/211131605-60836c1f-9fe5-4567-a6f1-6afb2dfce9b6.svg)

## Summary

### What I Learned

1. **AWS S3 Integration**: Gained practical experience in integrating and automating interactions with AWS S3 using Python.

### Challenges
- **AWS Permissions and Security**: Ensuring secure and correct AWS permissions for script functionality.
- **Handling Large Datasets**: Developing efficient ways to process and handle large datasets without overwhelming system resources.

### Future Improvements
- [ ] **Error Handling**: Implement more robust error handling, especially for network issues and S3 access problems.
- [ ] **User Interface**: Develop a GUI for easier parameter configuration and progress tracking.
- [ ] **Extended Format Support**: Increase the range of document formats supported by the script.
