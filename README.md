# Audio Dataset 

This repo contains release details and metadata for the Common Voice dataset. 
Please visit https://commonvoice.mozilla.org/datasets to download the full dataset.

# GCS Audio Dataset Uploader

This project contains a Python script that uploads a large dataset of over 2 million audio files to a Google Cloud Storage (GCS) bucket using concurrent uploads. The dataset includes audio files from Mozilla's Common Voice corpus.

## Features
- Uploads audio files to a GCS bucket.
- Supports concurrent uploads for efficient processing.
- Python script can be customized to handle various datasets and file formats.

## Prerequisites
- Python 3.x
- Google Cloud SDK
- A Google Cloud project with a GCS bucket.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Mozilla_Real_Common_voice.git

Install the required Python packages:pip install google-cloud-storage
Set up Google Cloud authentication by exporting your service account JSON file:

