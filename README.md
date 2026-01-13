# ICV-project

# Traffic Sign Detection

## Project Overview
This project implements an object detection pipeline inspired by YOLO (You Only Look Once) for detecting traffic signs.  
The model is trained on the GTSDB (FullIJCNN2013) dataset and predicts both bounding boxes and class labels for traffic signs in images.

---

## Team Members
- Pierre BAROUT 
- Alan CARCEL  
- Etienne Gastard
- Quentin THIBAULT 

---

## Dataset
- **Name**: GTSDB – FullIJCNN2013  
- **Data**: `.ppm` images with corresponding annotations  
- **Classes**: multiple types of traffic signs (43 classes)  
- **Format**: annotations 

## Dataset structure:
```text
FullIJCNN2013/
└── FullIJCNN2013/
    ├── images/
    ├── Readme.txt/
    └── gt.txt
```

## Limitations

- Long training time
- Simplified model architecture
- Limited post-processing
- Visual results may be unstable

## Run the code

Please find the "requirements.txt" file to download the necessary libraries
