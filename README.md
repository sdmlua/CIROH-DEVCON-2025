# FIMserv v.1.0: A Tool for Streamlining Flood Inundation Mapping Using the United States Operational Hydrological Forecasting Framework

We have developed the OWP HAND-FIM ‘as a service’ (FIMserv), an open-source Python toolset for running the FIM generation procedures using NWM operational input data. This approach leverages virtual .env files to define essential environment variables, such as input and output directories for the OWP HAND-FIM’s FIM generation module. By replicating Docker’s role in environment configuration in a simplified manner, this method bypasses containerization while maintaining a consistent and portable setup. The script dynamically adjusts to the local system’s structure, ensuring dependencies and file paths are properly aligned for successful execution. 
In the workshop, We will demonstrate the following functionalities--
1.	User-friendly and customizable notebook interface
2.	Embedded visualization
3.	Flexibility to run both locally and on the cloud (Google Colab)
4.	Domain filtering based on stream order
5.	Multi-watershed simulations for different flood events
6.	Capability to process both retrospective and forecast (short- and long-range) NWM discharge for FIM generation
7.	Visualization of SRCs for any reach within a HUC-8 boundary
8.	Comparison of USGS and NWMv3.0 retrospective discharge data.
9.	Ability to subset from the HUC-8 scale FIMs based on user-defined polygons or coordinates. 
10.	Automatic FIM generation using USGS discharge data.

[For more information, refer to the original GitHub page of FIMserv](https://github.com/sdmlua/FIMserv).

***This repository contains the FIMserv Python framework, example dataset, and installation information for the participants of CIROH-DEVCON-2025. We have also attached the pre-print of our manuscript (currently under review) where we discussed in detail about the developed modules and their applications.***

# Installation (*for macOS/Windows)
1) Install Anaconda
2) Right-click on the shared CIROH-DEVCON folder (CIROH-DEVCON.zip)and select ‘New Terminal at Folder’ (use **Anaconda Prompt** on Windows)
3) Crete a virtual enviroment from the terminal: ***conda create --name cirohdevcon python==3.10***
4) Activate the virtual enviroment : ***conda activate cirohdevcon***
5) Install the package from terminal : ***pip install fimserve***
6) Install the notebook : ***pip install jupyter notebook***
7) Launch Jupyter Notebook and upload **FIMserve.ipynb**
(* You can do`pip install fimserve` after launching the notebook)

# In case of any installation problem in Local machine, User can use the Google Colab version of FIMserve

**FIMserv in Google Colab** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pXWiFKi_vWEq1jxfmFuXVYfDMmfXu0r2)

***Install QGIS/ARCGIS to visualize the flood raster***

For any queries, rerach out to : abaruah@ua.edu, sdhital@crimson.ua.edu
