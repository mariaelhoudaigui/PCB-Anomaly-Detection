

# **Description**:
This project is designed to identify defects on PCBs (Printed Circuit Boards) using computer vision and deep learning techniques. The application automates the detection of faults , improving quality control in industrial environments.

# **Features**:
- **Defect Detection in PCB Images**: Analyze static images of PCBs to identify and localize defects, including:
  - **Mouse Bite**: Small irregularities or gaps on the PCB edges.
  - **Missing Hole**: Missing or incomplete drill holes.
  - **Short**: Unintended connections between conductive paths.
  
- **Batch Processing**: Efficiently process multiple PCB images in a single run, generating reports for entire datasets.

- **Exportable Results**: Save annotated images with bounding boxes and detailed defect logs for further analysis or reporting.

- **High Accuracy**: Leverages a fine-tuned YOLOv8 Nano model trained for 100 epochs, achieving precise detection while maintaining computational efficiency.

---

# **Technologies Used**:

- **Roboflow**: Utilized for preparing and annotating the PCB dataset, ensuring high-quality input data for model training.
- **YOLOv8 (Ultralytics)**: A state-of-the-art object detection model. The version (`yolov8n.pt`) was fine-tuned on a custom dataset with 3 defect classes.
- **OpenCV**: Used for preprocessing PCB images and visualizing detection results.


