# **Description**:
This project is designed to identify defects on PCB (Printed Circuit Boards) using advanced computer vision and deep learning techniques. The application focuses on automating the detection of faults to improve quality control in industrial environments. It operates entirely through scripts without requiring a graphical user interface, ensuring efficient and reliable processing.

# **Features**:

Defect Detection in PCB Images: Analyze static images of PCBs to identify and localize defects, such as missing components, misalignments, or soldering issues.
Batch Processing: Process multiple images in a single run, generating defect reports for entire datasets.
Exportable Results: Save annotated images and defect logs for further analysis and reporting.
High Accuracy: Leverages a fine-tuned YOLOv8 (You Only Look Once) model to ensure precise detection of various types of defects.

# **Technologies Used**:

Roboflow: Used for dataset preparation and annotation, creating a high-quality training set.
YOLOv8 (Ultralytics): A cutting-edge object detection model, fine-tuned on a custom PCB defect dataset for optimal performance.
OpenCV: For preprocessing PCB images and post-processing detection results.
Python Scripts: The application is implemented in Python, providing a flexible and script-based workflow for defect detection.
