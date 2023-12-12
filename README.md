# AGU-2023-Joseph-Nied-Poster
GitHub repository for online/virtual results for Joseph Nied's poster at the American Geophysical Union (AGU) 2023, titled "Advancing Global Cloud Detection in Satellite Imagery with Spatial and Spectral Awareness via Deep Learning". Within this repository, the AGU Poster and online only results are displayed. Online results include animations of the training process of our best models in how they are able to learn cloud textures and features within satellite remote sensing imagery from the Moderate Resolution Imaging Spectrometer (MODIS) and the Multi-angle Imaging SpectroRadiometer (MISR).

# MISR Training Movie:
Animations are depicted in the left column for our best U-Net model that uses Bi-Tempered Logistic Loss for MODIS and MISR each. Models are trained using t<sub>1</sub>=1.0 and t<sub2</sub>=2.5. Training labels are from the MODIS cloud masking algorithm (MOD35) and the MISR cloud masking algorithm (RCCM (Radiometric Camera-by-camera Cloud Mask)). The left column depicts the models and the right depicts the ground truth.

<p align="center">
Example 1:
<img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/Example-1.gif" alt="MISR Example 1 Training" width="400" height="400" loop=1><img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/Example-1-RCCM.png" alt="MISR Example 1 RCCM" width="400" height="400">

Example 2:
<img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/Example-2.gif" alt="MISR Example 2 Training" width="400" height="400" loop=1><img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/Example-2-RCCM.png" alt="MISR Example 2 RCCM" width="400" height="400">

Example 3:
<img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/Example-3.gif" alt="MISR Example 3 Training" width="400" height="400" loop=1><img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/MISR/Example-3-RCCM.png" alt="MISR Example 3 RCCM" width="400" height="400">
</p>

# AGU 2023 Poster:

<img src="https://github.com/jdn8608/AGU-2023-Joseph-Nied-Poster/blob/main/POSTER/Joseph_Nied-AGU%2BMISR-2023.png" alt="AGU 2023 Poster - Joseph Nied">
