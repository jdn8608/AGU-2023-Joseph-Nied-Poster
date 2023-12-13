# AGU-2023-Joseph-Nied-Poster
GitHub repository for online/virtual results for Joseph Nied's poster at the American Geophysical Union (AGU) 2023, titled "Advancing Global Cloud Detection in Satellite Imagery with Spatial and Spectral Awareness via Deep Learning". Within this repository, the AGU Poster and online only results are displayed. Online results include animations of the training process of our best models in how they are able to learn cloud textures and features within satellite remote sensing imagery from the Moderate Resolution Imaging Spectrometer (MODIS) and the Multi-angle Imaging SpectroRadiometer (MISR).

# Contact
Email: jdnied2@illinois.edu
LinkedIn: https://www.linkedin.com/in/joseph-nied-1621bb1a2

# AGU 2023 Poster:

<img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/POSTER/Joseph_Nied-AGU%2BMISR-2023.png" alt="AGU 2023 Poster - Joseph Nied">

# Bi-Tempered Logistic Loss Visualizations on MODIS Imagery
Animations depict the effects of Bi-Tempered Logistic Loss parameterization during the training process on MODIS imagery, using MOD35 (current MODIS Cloud Mask) as ground truth. MOD35, has known issues with picking up small & sub-pixel cumulus clouds. We attempt to pick these features up by tempering the evaluation during the learning process. t<sub>1</sub> relaxes the effects of datapoints far from the decision boundary, while t<sub>2</sub> relaxes the effects of datapoints near the decision boundary.

Example 1:

<p align="center">
<img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MODIS/MODIS-Example-1.gif" alt="MISR Example 1 Training" width="400" height="400" loop=1>
</p>

Example 2:

<p align="center">
<img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MODIS/MODIS-Example-2.gif" alt="MISR Example 1 Training" width="400" height="400" loop=1>
</p>


# MISR Training Movie:
Animations are depicted in the left column for our best U-Net model that uses Bi-Tempered Logistic Loss for MODIS and MISR each. Models are trained using t<sub>1</sub>=1.0 and t<sub>2</sub>=2.5. Training labels are from the MODIS cloud masking algorithm (MOD35) and the MISR cloud masking algorithm (RCCM (Radiometric Camera-by-camera Cloud Mask)). The left column depicts the models and the right depicts the ground truth.

Example 1:  

<p align="center">
<img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/MISR-Example-1.gif" alt="MISR Example 1 Training" width="400" height="400" loop=1><img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/Example-1-RCCM.png" alt="MISR Example 1 RCCM" width="400" height="400">  
</p>

Example 2:  

<p align="center">
<img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/MISR-Example-2.gif" alt="MISR Example 2 Training" width="400" height="400" loop=1><img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/Example-2-RCCM.png" alt="MISR Example 2 RCCM" width="400" height="400">  
</p>

Example 3:  

<p align="center">
<img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/MISR-Example-3.gif" alt="MISR Example 3 Training" width="400" height="400" loop=1><img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/Example-3-RCCM.png" alt="MISR Example 3 RCCM" width="400" height="400">  
</p>

