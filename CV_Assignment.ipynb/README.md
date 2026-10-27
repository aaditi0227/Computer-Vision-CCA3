# Computer Vision CCA3 — Units 3, 4 and 5

## 1. Project Overview

This repository contains the source code and experimental results for the Computer Vision CCA3 practical assignment. It covers image restoration, image segmentation, feature extraction, image matching, and object recognition using Python and Jupyter Notebook.

## 2. Assignment Tasks

### Task 1: Image Restoration and Segmentation

**Notebook:** `Task1_Image_Restoration.ipynb`

Techniques implemented:
- Gaussian noise and salt-and-pepper noise addition
- Median filtering and Gaussian filtering
- Image quality evaluation using PSNR and SSIM
- Binary image thresholding
- Erosion, dilation, opening, and closing
- Canny edge detection
- Watershed segmentation
- Comparison of restoration and segmentation results

### Task 2: Feature Extraction and Image Matching

**Notebook:** `Task2_Feature_Extraction.ipynb`

Techniques implemented:
- Histogram of Oriented Gradients (HOG) feature extraction and visualization
- SIFT keypoint detection and descriptor extraction
- SIFT feature matching between images
- Matching experiments after image rotation and resizing
- Comparison of feature-matching results

### Task 3: Object Recognition Using Viola–Jones and YOLO

**Notebook:** `Task3_Object_Recognition.ipynb`

Techniques implemented:
- Face detection using a pretrained Haar Cascade classifier
- Object detection using a pretrained YOLOv8 model
- Bounding boxes, object labels, and confidence scores
- Comparison of detection results
- Inspection of possible missed or incorrect detections

### Task 4: Video Motion Estimation

This task must be completed and added before final submission.

Required techniques:
- Consecutive video frame extraction
- Frame differencing
- Gaussian Mixture Model (GMM)-based background subtraction
- Lucas–Kanade optical flow
- Visualization of foreground masks and motion vectors
- Comparison of the motion-estimation techniques

## 3. Project Structure

```text
CV_Assignment/
├── Task1_Image_Restoration.ipynb
├── Task2_Feature_Extraction.ipynb
├── Task3_Object_Recognition.ipynb
├── Task4_Motion_Estimation.ipynb
├── README.md
├── requirements.txt
├── images original/
├── video original/
├── outputs/
├── task1_outputs/
├── task2_outputs/
└── task3_outputs/
```

The Task 4 notebook should be added after implementation. The folder structure above describes the intended organization; retain the actual folder names used in your project.

## 4. Software Requirements

- Python 3.10 or later
- Jupyter Notebook
- OpenCV
- NumPy
- Matplotlib
- scikit-image
- Pandas
- Ultralytics YOLO
- IPython

## 5. Installation Instructions

### Step 1: Install Python

Install Python from https://www.python.org/downloads/ if it is not already installed.

### Step 2: Open the project folder

Open Command Prompt in the project directory.

### Step 3: Install dependencies

Run:

```bash
pip install -r requirements.txt
```

### Step 4: Start Jupyter Notebook

Run:

```bash
jupyter notebook
```

Open the required notebook in your browser and execute the cells from top to bottom.

## 6. Input Dataset Instructions

Use the original photograph captured using your own mobile phone or camera. For feature extraction and matching, use a second photograph of the same object or scene.

Preserve the original, unedited photograph and organize input images in the designated image folder.

Use your own self-recorded video for the video-based tasks. The assignment specifies an original video of approximately 15–30 seconds containing a moving person or object and sufficient background detail.

Update file paths inside the notebooks if your local folder structure differs from the paths in the code.

Large raw video files should be uploaded to Google Drive rather than unnecessarily committed to GitHub. Include instructions or a link for accessing the video when required and permitted by your instructor.

## 7. Outputs and Results

The notebooks display processed images, restored images, binary masks, morphological results, edge maps, watershed segmentation, HOG visualizations, SIFT keypoints, feature matches, object detection results, and comparison measurements.

Selected result images and comparison files should be stored in the relevant output folders.

All outputs should have appropriate captions and brief explanations in the technical report.

## 8. Technical Documentation

The final technical report should include:
- Assignment objectives
- Details of the original input photograph and video
- Algorithms and implementation steps
- Source code descriptions
- Output images and explanations
- Comparison tables and performance measurements
- Conclusions
- GitHub repository URL
- Project explanation video link

## 9. Repository

**GitHub Repository URL:** Add your repository URL here after creating and pushing the project.

## 10. Final Submission Checklist

- [ ] Source notebooks for all four tasks
- [ ] README and requirements files
- [ ] Original input photograph and second matching photograph
- [ ] Original self-recorded video, shared through the required Google Drive location
- [ ] Relevant example outputs and comparison results
- [ ] Completed technical report
- [ ] GitHub repository URL included in the report
- [ ] Project explanation video of approximately 5–8 minutes
- [ ] Required instructor access granted
- [ ] All notebooks tested and executed successfully

**Note:** The repository should contain the completed assignment source

## Input Dataset Instructions

### Original Photographs

1. Capture an original photograph using your own mobile phone or camera.
2. Preserve the original, unedited image.
3. Use a suitable photograph for image restoration and segmentation.
4. Use a second photograph of the same object or scene for feature extraction and image matching.
5. Store the photographs in the `images original/` folder.
6. Update the image paths in the notebooks if necessary.

### Original Video

1. Record your own video of approximately 15–30 seconds.
2. Include a moving person or object and sufficient background detail.
3. Keep the camera reasonably stable for part of the recording.
4. Preserve the original, unedited video.
5. Store the video in the `video original/` folder on your computer.

### Large Video Files

Large raw videos should be uploaded to the Google Drive location provided by the instructor rather than unnecessarily committed to GitHub. Include the appropriate Drive link or access instructions in the technical report when required.

### Reproducing the Experiments

1. Clone or download the GitHub repository.
2. Install the packages using `python -m pip install -r requirements.txt`.
3. Obtain the original input files from the project folders or the instructor-approved Google Drive location.
4. Place the files in the expected folders.
5. Update the paths in the notebooks to match the local setup.
6. Run each notebook from top to bottom.
7. Check that the output images, tables, and measurements are generated successfully.
