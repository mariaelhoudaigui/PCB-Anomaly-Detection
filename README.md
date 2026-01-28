

# **Description**:
This project automates the detection of defects in Printed Circuit Boards (PCBs) using computer vision and deep learning techniques. The application is designed to enhance quality control in industrial production lines, improving efficiency and reducing human error. By leveraging the YOLOv8 object detection model, it can quickly and accurately identify faults in PCB images, significantly improving the overall production process.

# **Features**:
- **Defect Detection in PCB Images**: Analyze static images of PCBs to identify and localize defects, including:
  - **Mouse Bite**: Small irregularities or gaps on the PCB edges.
  - **Missing Hole**: Missing or incomplete drill holes.
  - **Short**: Unintended connections between conductive paths.
  
- **Batch Processing**:The tool supports processing multiple PCB images at once, making it suitable for large-scale industrial environments. This feature allows users to run the detection on an entire dataset, saving time and resources.
- **Exportable Results**: Annotated images are generated with bounding boxes highlighting defects, along with detailed logs containing defect descriptions, making it easier to document, analyze, and report.
- **High Accuracy**: The model, based on YOLOv8 Nano, has been fine-tuned for 100 epochs, ensuring precise detection while maintaining computational efficiency. This lightweight version of YOLO is designed for use in industrial settings where quick and accurate results are essential.


# **Technologies Used**:

- **Roboflow**: Utilized for preparing and annotating the PCB dataset, ensuring high-quality input data for model training.
- **YOLOv8 (Ultralytics)**: A state-of-the-art object detection model. The version (`yolov8n.pt`) was fine-tuned on a custom dataset with 3 defect classes.
- **OpenCV**: Used for preprocessing PCB images and visualizing detection results.


# **Demonstration**
[image](pcb.png)
