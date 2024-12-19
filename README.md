# Hosting Web Apps on Google Colab

## Overview
This project provides a convenient and cost-effective solution for testing AI-powered web applications using Google Colab Notebooks. It eliminates the need for hardware upgrades or expensive cloud services, making it accessible for developers and researchers.

## Motivation
The primary motivation behind this initiative was to develop a simple and affordable approach for debugging and testing web applications. By leveraging Google Colab, users can sidestep significant infrastructure investments while retaining the flexibility and power needed for development.

## Requirements
The provided examples meet the essential requirements of the project, offering a robust starting point for further enhancements and customization.

## How It Works
The project utilizes Node.js, particularly the npm package "localtunnel" (now updated to use ngrok for improved reliability), along with other npm packages such as http-server. This setup facilitates the creation of a zero-configuration command-line HTTP server, suitable for serving static files or frameworks like Django or Streamlit. This environment enables users to serve and share web applications globally from Google Colab—a Jupyter notebook platform hosted on Google Cloud—while leveraging free GPUs for advanced AI-powered applications.

## Getting Started

### Step 1
Navigate to the [Samples](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/tree/main/samples) directory and select the notebook that aligns with your project type.

### Step 2
Open the chosen sample notebook and follow the provided instructions. Locate the following line:

![Screenshot displaying where to find Global IP](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/blob/main/Screenshots/IP_screeshot.png)

Copy the Global IP as shown in the screenshot.

### Step 3
Click on the APP link provided in the notebook. A preliminary page will load before redirecting to the main page. Paste the copied Global IP address into the specified field as shown:

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
This project is primarily designed for simple development purposes. Notable limitations include:
1. **Reliability:** Localtunnel’s lack of maintenance prompted a shift to ngrok, which offers improved performance but may still encounter occasional issues.
2. **Complexity:** Current examples are limited to basic use cases, with more advanced examples under development.

## What's New
All basic notebooks have been updated to use ngrok instead of localtunnel, addressing long-standing reliability issues. The notebooks are now fully up-to-date as of **December 19, 2024**.
