# PCA--PROJECT

# **Image and Signal Processing Project**

This project is designed to perform either image or signal processing on large datasets. It efficiently handles hundreds of small or tens of large images and CSV-based signal data. The primary goal is to demonstrate efficient processing using parallel execution, error handling, and progress tracking.

Features
Image Processing: Converts images to grayscale using OpenCV and saves them to the output directory.
Signal Processing: Processes large CSV files containing signal data by applying a simple moving average filter.
Parallel Execution: Uses ThreadPoolExecutor to speed up the processing of large datasets.
Progress Tracking: Displays progress bars using tqdm for real-time feedback on processing status.
Error Logging: Logs any errors during image or signal processing without stopping the overall execution.
Requirements
To run this project, you will need the following dependencies:

pip install -r requirements.txt
Python 3.6+
opencv-python for image processing
pandas for handling CSV signals
numpy for numerical operations
tqdm for progress tracking
Pillow for handling images
Usage
Step 1: Organize Your Data
Place your image files (JPEG, PNG) and CSV signal files in the data/ directory. Ensure that CSV files have a column named signal to apply the filter correctly.

Step 2: Run the Script
To run the script and start processing your data: bash python main.py The processed files will be saved in the output/ directory.

Step 3: Monitor Progress
You can monitor the progress of the processing tasks with real-time progress bars. Any errors encountered during processing will be logged in processing_errors.log.

Improvements & Future Work
Implement more advanced image processing techniques (e.g., edge detection, segmentation). Extend signal processing to handle other types of filtering (e.g., Fourier transform).

Input Image

![image](https://github.com/user-attachments/assets/5bba18f4-4ce8-4d5a-89ab-9f50f9ec73e6)


Output image

![Screenshot 2024-11-25 221526](https://github.com/user-attachments/assets/4953545d-9ddf-4b3d-9f66-3a94dab9c307)


