# sensation
This is work for Heritage Jam 2021 and explores mapping work I have been doing as part of the CCAD-CRANE project.

## Requirements
This project will create an html page with a Leaflet map that is designed to run on a smartphone and plot the user's location.
To create the map and test it:
* A computer to run a Python Jupyter Notebook (such as Google Colab)

To run the map on a phone
* A web server with TLS to serve up the map webpage using https.
* A smart phone


## setup / installation
This can be run from a notebook in Google Colab:  https://github.com/jeffblackadar/sensation/blob/main/installer.ipynb
In Google Drive - create a directory example: "github"

Open a temporary notebook in Google Colab

Mount the Google Drive
+ Code
```
from google.colab import drive
drive.mount('/content/drive')
```

List the directory
+ Code
```
!ls
```

Change to the parent directory
+ Code
```
%cd /content/drive/MyDrive/github
```

Print working directory
+ Code
```
!pwd
```
/content/drive/MyDrive/github

Clone the repository
+ Code
```
! git clone https://github.com/jeffblackadar/sensation/
```

Go back into Google Drive 
select sensory_map_generator.ipynb and Open in Google Colab




Credit to https://medium.com/@ashwindesilva/how-to-use-google-colaboratory-to-clone-a-github-repository-e07cf8d3d22b
