# Hosting-Web-Apps-on-Google-Colab
Using Node.js in Colab Notebooks to deploy different kinds of web apps temporarily for debugging and testing Purposes

# Motivation

I wanted to make an easy way to test AI powered webapps before deployment without upgrading my hardware or using expensive cloud services

# Requirements

All of the currently available examples are basic examples so most of the requirements are already met in the examples

# How it works

The basic concept here involves using Node.js, specifically the npm package "localtunnel," alongside other npm packages such as http-server. This setup creates a simple, zero-configuration command-line HTTP server for serving static files or frameworks such as Django or Streamlit. It allows users to serve and share web applications with the world from Google Colab, a Jupyter notebook environment hosted on the Google Cloud platform. Google Colab provides a browser-based interface for writing and executing Python code and also offers access to free GPUs, which is beneficial for more sophisticated AI-powered web applications.

# How to Use

### Step 1: go to [Samples](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/tree/main/samples) and select the notebook which fits the type of your project
### Step 2: after opening any of the sample notebooks and going through each step you'll eventually find the following line:
![where to find Global IP](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/blob/main/Screenshots/IP_screeshot.png)
Make sure to copy the IP like in the above screenshot 
### Step 3: after clicking on the link of the APP you will be greeted with a page before getting directed to the main page to get directed to the main page paste the copied Global IP address like so.
![Where to use Global IP](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/blob/main/Screenshots/IP_usage_screenshot.png)


# Screenshots
## Static website Sample Preview:
![Static website example](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/blob/main/Screenshots/basicWebappPreview.png)

## Django Sample preview:
![Static website example](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/blob/main/Screenshots/DjangoPreview.png)

## Streamlit Sample Preview:
![Static website example](https://github.com/UndeadZed/Hosting-Web-Apps-on-Colab/blob/main/Screenshots/StreamlitPreview.png)



# Credits

Big credit to [FahimFBA](https://github.com/FahimFBA) whom we used his project in one of the examples.


# Limitations
No Google drive linked examples are made yet since all the current examples are just basic examples

# What's new
Simple Python Django implementation example notebook in Colab

# Future updates

I will be focusing on adding usable example which use different front and backend technologies to make AI powered APPs

# Notes
feel free to contribute to this repo and add additional examples


