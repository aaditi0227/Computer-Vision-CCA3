# Computer Vision CCA3 Assignment

## Overview

This repository contains the implementation of the Computer Vision CCA3 assignment. It demonstrates image processing, feature extraction, object recognition, and video motion estimation using Python and computer vision libraries.

## Objectives

- Perform image restoration and segmentation.
- Extract image features and perform image matching.
- Detect and recognize objects using Viola–Jones and YOLO.
- Estimate motion in video using frame differencing, background subtraction, and optical flow.

## Tasks Implemented

### Task 1: Image Restoration and Segmentation

This task explores image noise removal and segmentation techniques.

**Techniques used:**
- Gaussian noise and salt-and-pepper noise
- Gaussian and median filtering
- Image quality evaluation using PSNR and SSIM
- Binary thresholding
- Morphological operations
- Canny edge detection
- Watershed segmentation

**Outputs:** Restored images, edge maps, thresholded images, segmentation results, and image quality metrics.

### Task 2: Feature Extraction and Image Matching

This task extracts and compares visual features from images.

**Techniques used:**
- Histogram of Oriented Gradients (HOG)
- Scale-Invariant Feature Transform (SIFT)
- Keypoint and descriptor extraction
- Feature matching
- Matching under image rotation and resizing

**Outputs:** HOG visualizations, SIFT keypoints, feature-matching images, and comparison results.

### Task 3: Object Recognition Using Viola–Jones and YOLO

This task compares traditional object detection with deep-learning-based object detection.

**Techniques used:**
- Viola–Jones detection using Haar Cascade classifiers
- YOLOv8 object detection
- Bounding-box visualization
- Confidence-score analysis
- Video frame extraction and detection comparison

**Outputs:** Detection images, extracted video frames, and CSV comparison results.

### Task 4: Video Motion Estimation

This task covers motion estimation techniques for video analysis.

**Techniques to be implemented and evaluated:**
- Frame differencing
- Gaussian Mixture Model (GMM) background subtraction
- Lucas–Kanade optical flow

**Note:** Add the Task 4 notebook and its generated outputs before submission if they are not yet present in the repository.

## Project Structure

```text
CV_Assignment/
├── images original/
│   ├── image1.jpeg
│   └── image2.jpeg
├── video original/
│   └── video1.mp4
├── outputs/
├── task1_outputs/
├── task2_outputs/
├── task3_outputs/
├── Task1_Image_Restoration.ipynb
├── Task2_Feature_Extraction.ipynb
├── Task3_Object_Recognition.ipynb
├── Task4_Video_Motion_Estimation.ipynb
├── CV_Assignment_Technical_Report.docx
├── requirements.txt
└── README.md
```

The listed Task 4 notebook should be included once it has been created. The exact files and output folders may vary depending on the final implementation.

## Technologies Used

- Python
- Jupyter Notebook
- OpenCV
- NumPy
- Matplotlib
- scikit-image
- Pandas
- Ultralytics YOLOv8

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Computer-Vision-CCA3.git
cd Computer-Vision-CCA3
```

Replace `YOUR_USERNAME` with your GitHub username.

### 2. Create a virtual environment (optional)

```bash
python -m venv venv
```

On Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the required task notebook and execute its cells in order.

## Input Dataset

The project uses image inputs and a video input for the computer vision experiments.

- Place the required images inside `images original/`.
- Place the input video inside `video original/`.
- Update notebook paths if your input files are stored elsewhere.
- Ensure that all required input files are available before running the notebooks.

Use images and videos that you are permitted to use and share.

## Results and Outputs

Generated results are organized into task-specific output folders:

- `task1_outputs/` — image restoration, segmentation, and quality metrics.
- `task2_outputs/` — feature extraction, keypoints, matching visualizations, and comparisons.
- `task3_outputs/` — object detection results and comparison files.
- `outputs/` — additional results generated during experimentation.

The technical report documents the experiments, observations, and conclusions.

## Technical Report

The repository includes `CV_Assignment_Technical_Report.docx`, which documents the work carried out for the assignment. Update the report to include the final results and observations from all four tasks.

## Limitations

- Detection accuracy depends on image quality, object visibility, and the selected model.
- Feature matching may vary with changes in scale, rotation, and lighting.
- Results depend on the input images, video, and installed library versions.
- YOLOv8 may download model files or require additional setup during its first run.

## Conclusion

This assignment demonstrates key computer vision techniques for image restoration, segmentation, feature extraction, object detection, and motion estimation. It combines traditional image-processing methods with modern deep-learning-based detection to analyze images and video.

## Author

**Student:** Add your name  
**Course:** MCA  
**Assignment:** Computer Vision CCA3
