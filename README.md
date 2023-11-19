# Hosting Web Apps on Google Colab

## Overview
The project aims to provide a convenient method for testing AI-powered web apps before deployment using Google Colab Notebooks, without the need to upgrade hardware or utilize expensive cloud services.

## Motivation
The motivation behind this initiative stemmed from the need to create a straightforward approach for debugging and testing purposes without substantial cost or infrastructure updates.

## Requirements
The existing examples provided fulfill most of the project's requirements, providing a strong foundation for further development.

## How it Works
Utilizing Node.js, with a focus on the npm package "localtunnel," in conjunction with other npm packages such as http-server, enables the creation of a straightforward, zero-configuration command-line HTTP server for serving static files or frameworks like Django or Streamlit. This environment allows users to serve and share web applications globally from Google Colab, a Jupyter notebook environment hosted on the Google Cloud platform, with the added benefit of access to free GPUs for more advanced AI-powered web applications.

## Getting Started
### Step 1
Navigate to [Samples](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/tree/main/samples) and select the notebook that aligns with your project type.
### Step 2
After opening any of the sample notebooks and following the outlined instructions, locate the line:
![Screenshot displaying where to find Global IP](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/blob/main/Screenshots/IP_screeshot.png)
<br>Ensure to copy the IP as depicted in the above screenshot.
### Step 3
Upon clicking on the APP link, you will encounter a preliminary page before being directed to the main page. To proceed to the main page, paste the previously copied Global IP address in the specified location:
![Screenshot indicating where to use Global IP](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/blob/main/Screenshots/IP_usage_screenshot.png)

## Screenshots
### Static Website Sample Preview
![Preview of the static website example](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/blob/main/Screenshots/basicWebappPreview.png)

### Django Sample Preview
![Preview of the Django example](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/blob/main/Screenshots/DjangoPreview.png)

### Streamlit Sample Preview
![Preview of the Streamlit example](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/blob/main/Screenshots/StreamlitPreview.png)

## Credits
Special thanks to [FahimFBA](https://github.com/FahimFBA) for contributing to one of the example projects.

## Limitations
At present, no examples linked to Google Drive have been created, as the current samples primarily focus on basic scenarios.

## What's New
Addition of a simple Python Django implementation example notebook in Colab.
