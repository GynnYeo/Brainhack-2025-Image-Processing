# Brainhack-2025-Image-Processing
When participating in DSTA's brainhack 2025, there was a component on post processing images from Landsat 8 satellite. This project aims to automate the process of creating various composite images from landsat 8 and extract useful relevant information. Our team received an honourable mention of best image processing in the hackathon.

## Landsat 8 
Landsat 8 is one of the satellites orbiting Earth launched as part of NASA and the U.S. Geological Survey's (USGS) long-running Landsat program, which has been monitoring Earth's surface since 1972.

### Spectral Bands & Applications
Landsat 8 collects data in 11 spectral bands (9 from OLI, 2 from TIRS).
#### Operational Land Imager (OLI)
- Nine spectral bands, including a pan band:
  - Band 1 Coastal Aerosol (0.43 - 0.45 µm) 30 m
  - Band 2 Blue (0.450 - 0.51 µm) 30 m
  - Band 3 Green (0.53 - 0.59 µm) 30 m
  - Band 4 Red (0.64 - 0.67 µm) 30 m
  - Band 5 Near-Infrared (0.85 - 0.88 µm) 30 m
  - Band 6 SWIR 1(1.57 - 1.65 µm) 30 m
  - Band 7 SWIR 2 (2.11 - 2.29 µm) 30 m
  - Band 8 Panchromatic (PAN) (0.50 - 0.68 µm) 15 m
  - Band 9 Cirrus (1.36 - 1.38 µm) 30 m
#### Thermal Infrared Sensor (TIRS)
- Two spectral bands:
    - Band 10 TIRS 1 (10.6 - 11.19 µm) 100 m
    - Band 11 TIRS 2 (11.5 - 12.51 µm) 100 m

## Goal
Our aim was to create various composite images using permutations of different spectral band images. In creating these composite images, we can get a better understanding of the condition of the location of the image.

## Composite Images 
Below are examples of the composite images we came up with 
### Natural Colour Image 
![Natural Colour Image](/img2/432_natural_colour_image.png)
### False Colour Image (Colour Infrared Image)
![False Colour Image](/img2/543_color_infrared_image.png)
### NDVI Image
![NDVI Image](/img2/NDVI_image.png)
### Burn Scar Image
![Burn Scar Image](/img2/754_fire_and_burn_scar_image.png)



## References:
- https://www.usgs.gov/landsat-missions/landsat-8
- https://chatgpt.com/



