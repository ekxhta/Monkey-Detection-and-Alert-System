# Monkey Threat Detection - ML Module

This repository contains the YOLOv8-based model implementation for the Monkey Threat Detection and Alert System.

The system detects monkeys in video footage and is trained using a custom dataset from Roboflow. Training and testing are done in Google Colab, with data stored in Google Drive.

--

## Objective

To automatically detect monkeys in surveillance video and generate alerts to prevent intrusion or disturbances in hostel or campus areas.

---

## ML Details

- **Model**: YOLOv8 (YOLOv8l)
- **Platform**: Google Colab
- **Dataset**: Roboflow (YOLOv8 format)
- **Trained Weights**: `best.pt` stored on Google Drive

--

## Files

| File | Description |
|------|-------------|
| `Minor_training.ipynb` | Colab notebook for training |
| `Minor_testing.ipynb` | Colab notebook for testing |
| `drive_links.md` | Links to dataset, model, and test_
