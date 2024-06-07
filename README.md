# Microsoft-Teams-Meeting-Sentiment-Analysis
## Audio Transcription and Sentiment Analysis
This repository contains scripts for uploading audio files to Google Cloud Storage (GCS), transcribing them using the Google Cloud Speech-to-Text API, and analyzing the sentiment of the transcribed text using the Google Cloud Natural Language API.

Prerequisites
Google Cloud Platform account
Python 3.6 or higher
google-cloud-storage and google-cloud-speech Python libraries
### Setup
Clone the repository
Install the required Python libraries: pip install google-cloud-storage google-cloud-speech google-cloud-language

Set up authentication:
Generate a service account key in your Google Cloud Platform (GCP) project and download the JSON key file.
Set the environment variable GOOGLE_APPLICATION_CREDENTIALS to the path of the downloaded JSON key file.
Replace the following variables in the script transcribe_and_analyze.py:

bucket_name: Your GCS bucket name
source_file_name: Path to your local audio file
destination_blob_name: Desired name for the file in GCS
Usage
Run the script transcribe_and_analyze.py to upload the audio file to GCS, transcribe it, and analyze the sentiment.

Note
Remember to change the credentials for the Google API accordingly before running the script.

Make sure to replace your-username and your-repository with your GitHub username and repository name, respectively. Also, ensure to update the script with your actual GCS bucket name, local file path, and desired GCS file name.
