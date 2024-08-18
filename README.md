# Dicom Viewer

Dicom Viewer is a Python desktop application designed for viewing and managing DICOM files (.dcm). The application allows users to visualize axial, sagittal, and coronal planes for all files in a dataset by specifying the path to the folder containing the .dcm files. Additionally, it features a cine (movie) mode for sequentially displaying and navigating through all slices of the dataset or a specified folder.

## Key Features

- Visualize axial, sagittal, and coronal planes of DICOM files.
- Cine (movie) mode for browsing through slices and pause at anytime.
- Display DICOM file information such as Patient Info, Modality, and Plane details.
- Ability to apply segmentation to each plane with the option to specify a threshold.
- Apply simple filters on DICOM, .jpg, or .png images using image processing techniques.
- Save processed images with applied filters.

## Project Aim

The project aims to streamline the process of navigating and interpreting datasets containing DICOM files, making it more accessible and efficient.

## Technologies Used

- **User Interface**: Designed in Qt Designer and handled by PyQt for interface processes.
- **pydicom**: Used for reading and processing DICOM file data.
- **Pandas**: Employed for data manipulation and handling.
- **OpenCV**: Utilized for image processing and applying filters in the image section.

## Instructions

- **Install Packages**: Run the following command to install required packages:

```python
pip install -r requirements.txt
```

- **Run Main File**: Execute the following command to run the main file:

```python
python -m dicom.py
```

---
