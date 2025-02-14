# Google-Docs-Markdown-Formatter
## Brief Description
This project is a Python script designed to run in Google Colab. It takes markdown meeting notes and converts them into a well-formatted Google Doc using the Google Docs API. The script handles authentication, formatting, and proper structuring, ensuring headings, checkboxes, and mentions are preserved.

## Setup Instructions
1. Open Google Colab.

2. Authenticate your Google account by running the script.

3. Enable the Google Docs API in your Google Cloud project.

4. Run the provided Python script in Colab.
## Required Dependencies
Ensure the following libraries are available:

* google.colab

* googleapiclient

* google.auth

* re

* markdown
- To install missing dependencies, run:
!pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client

## How to Run in Colab
1. Copy the provided script into a Google Colab notebook.

2. Run the first cell to authenticate Google services.

3. Execute the script to generate a formatted Google Doc.

4. Check your Google Drive for the newly created document.
