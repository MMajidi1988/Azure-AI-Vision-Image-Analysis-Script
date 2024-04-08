Azure AI Vision Image Analysis Script

This repository contains a Python script for analyzing images using Azure's AI Vision service. The script demonstrates how to use Azure Cognitive Services to analyze an image from a URL and extract information such as captions and optical character recognition (OCR) data.
Features

    Image Captioning: Extracts a caption describing the image.
    Optical Character Recognition (OCR): Reads text from the image.

Prerequisites

Before running this script, you will need:

    Python 3.x
    Azure AI Vision package from Azure Cognitive Services
    An Azure subscription and a Cognitive Services resource

Installation

    Clone the Repository:

    bash

git clone [URL to your repository]
cd [repository name]

Install Dependencies:

Ensure you have the required Python packages installed:

bash

    pip install azure-ai-vision

Configuration

    Set up Azure Cognitive Services:
        Create a Cognitive Services resource in your Azure subscription.
        Retrieve the endpoint URL and key for your resource.

    Configure Environment Variables:

    Set the following environment variables in your system:

    bash

    export VISION_ENDPOINT='[Your Azure Vision Endpoint URL]'
    export VISION_KEY='[Your Azure Vision Key]'

    Replace [Your Azure Vision Endpoint URL] and [Your Azure Vision Key] with your actual Azure credentials.

Usage

Run the script with:

bash

python [script_name].py

The script will analyze the image specified by the URL in the code and print out the caption and any text detected in the image.
Contribution

Feel free to fork this repository and contribute to improving the script. Please follow the existing coding style and add unit tests for any new or changed functionality.
License

This project is licensed under the MIT License.
