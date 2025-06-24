# Monkey Threat Detection - Machine Learning 

This repository contains the YOLOv8-based model implementation for the Monkey Threat Detection and Alert System.

The system detects monkeys in video footage and is trained using a custom dataset from Roboflow. Training and testing are done in Google Colab, with data stored in Google Drive.



### Objective

To automatically detect monkeys in surveillance video and generate alerts to prevent intrusion or disturbances in hostel or campus areas.



### ML Details

- **Model**: YOLOv8 (YOLOv8l)
- **Platform**: Google Colab
- **Dataset**: Roboflow (YOLOv8 format)
- **Trained Weights**: `best.pt` stored on Google Drive



### Files

| File | Description |
|------|-------------|
| `Minor_training.ipynb` | Colab notebook for training |
| `Minor_testing.ipynb` | Colab notebook for testing |
| `drive_links.md` | Links to dataset, model, and test|
| `training_notebook_link.md` | Quick link to training Colab |
| `testing_notebook_link.md` | Quick link to testing Colab |


### How to Use

1. Open the [training notebook](https://colab.research.google.com/drive/1ObUF6T62c5ZmMY_9DXXoE-WgeGKQ3Oal)
2. Mount Google Drive and load the dataset
3. Train YOLOv8 and export `best.pt`
4. Open [testing notebook](https://colab.research.google.com/drive/1weZWB6phiVk5I9WCWYz1cyeXgj60bS25)
5. Run detection on a video


### Drive Resources

See [`drive_links.md`](drive_links.md) for:
- Roboflow dataset
- Trained model (`best.pt`)
- Sample video


### Author

Ekshta Mishra  
Final-year CSE student, JUIT Solan  
ML Developer – Monkey Threat Detection and Alert System
