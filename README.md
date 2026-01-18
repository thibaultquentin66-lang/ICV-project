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
- **Link to the dataset**: https://benchmark.ini.rub.de/gtsdb_dataset.html

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
You can also use the computer vision environment to run the notebook.

## Vidéo

You can find the video link as follow (too big to be upload)
https://drive.google.com/file/d/1WlcxEg_H1ujg8er0k0Mbko_k4XiswZdr/view
