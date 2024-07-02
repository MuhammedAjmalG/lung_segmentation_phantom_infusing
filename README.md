# Lung Segmentation and 3D Printing Tool

## Overview

This project involves the development of a Python-based tool for segmenting lungs from 3D DICOM images using the LungMask library. The tool includes a Gradio interface for loading DICOM stacks, visualizing segmented lungs, and calculating mean HU values and infill density. Users can generate 3D structures such as tumors and fibrosis within the lung and export the results as STL files for 3D printing.

- **Dataset**: [DICOM Files from Cancer Imaging Archive](https://drive.google.com/drive/folders/1P0pRC4kRtEcam33Q-ulzm368nexF2KKb?usp=drive_link)
## Features

- **Lung Segmentation**: Uses the LungMask library to segment lungs from 3D DICOM images.
- **Visualization**: Gradio interface for loading DICOM stacks and visualizing segmented lungs.
- **3D Structure Generation**: Enables users to generate 3D structures within the lung.
- **Export to STL**: Exports the generated 3D structures as STL files for 3D printing.
- **Mean HU Calculation**: Calculates mean Hounsfield Unit values and infill density.

## Technical Skills

- **LungMask**: For lung segmentation from DICOM images.
- **DICOM Image Processing**: Using SimpleITK and Skimage libraries.
- **3D Visualization**: Visualization of segmented lungs and structures.
- **STL File Generation**: Exporting 3D structures as STL files.
- **Gradio Interface**: For user interaction and visualization.

## Requirements

- Python 3.x
- LungMask
- SimpleITK
- Skimage
- Gradio
- Numpy
- Pydicom

  
   
