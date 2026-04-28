# Week 04 - Task 1  
## YOLOv26 Dataset Configuration (Meta Files)

### Overview
In this task, we analyzed the meta configuration files used in a YOLOv26 dataset. These files define how the model understands dataset structure, class information, and annotations during training and validation.



### Key Components Studied

#### 1. YAML Configuration File (data.yaml)
- Defines dataset paths (train, validation)
- Specifies number of classes (`nc`)
- Contains class names (`names`)
- Acts as a bridge between dataset and model

#### 2. Dataset Directory Structure
- Images and labels are stored separately
- Organized into train and validation folders
- Each image has a corresponding label file

#### 3. Label Files
- Stored in `.txt` format
- Values are normalized (0–1)
- Each line represents one object


### Importance
- Ensures correct data loading
- Maintains consistency in class mapping
- Critical for successful model training
- Errors in these files can lead to incorrect predictions


### Report
The detailed analysis report is available here:

 Report (Download)(https://raw.githubusercontent.com/GADDAMADVITH/IIIT-H_ONLINE_INTERNSHIP_PROGRESS/main/WEEK-04/YOLOv26_report%20(1).docx)


### References
- https://docs.ultralytics.com/datasets/
- https://docs.ultralytics.com/datasets/detect/
- https://docs.ultralytics.com/usage/cfg/
- https://github.com/ultralytics/ultralytics
