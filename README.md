# FIMserv v.1.0: A Tool for Streamlining Flood Inundation Mapping Using the United States Operational Hydrological Forecasting Framework<img width="1724" alt="image" src="https://github.com/user-attachments/assets/d78e2cda-f660-47f2-ad31-bf73e836f4c1" />

This repository contains the FIMserv Python framework, example dataset, and necessary information for the participants of CIROH-DEVCON-2025.We have also attached the pre-print of our manuscript (currently under review)m where we discussed the developed modules and its different applications.
In this work, we present the OWP HAND-FIM ‘as a service’ (FIMserv), an open-source Python toolset for running the FIM generation procedures using NWM operational input data. This approach leverages virtual .env files to define essential environment variables, such as input and output directories for the OWP HAND-FIM’s FIM generation module. By replicating Docker’s role in environment configuration in a simplified manner, this method bypasses containerization while maintaining a consistent and portable setup. The script dynamically adjusts to the local system’s structure, ensuring dependencies and file paths are properly aligned for successful execution. FIMserv includes the following additional functionalities:
1.	User-friendly and customizable notebook interface
2.	Embedded visualization
3.	Flexibility to run both locally and on the cloud
4.	Domain filtering based on stream order
5.	Multi-watershed simulations for different flood events
6.	Capability to process both retrospective and forecast (short- and long-range) NWM discharge for FIM generation
7.	Visualization of SRCs for any reach within a HUC-8 boundary
8.	Comparison of USGS and NWMv3.0 retrospective discharge data.
9.	Ability to subset from the HUC-8 scale FIMs based on user-defined polygons or coordinates. 
10.	Inclusion of daily discharge from the Group on Earth Observations Global Water Sustainability (GeoGLOWS) for FIM generation.
11.	 Automatic FIM generation using USGS discharge data.


**FIMserv in Google Colab** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pXWiFKi_vWEq1jxfmFuXVYfDMmfXu0r2)



