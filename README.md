# Monkey Threat Detection - Machine Learning 

This repository contains the YOLOv8-based model implementation for the Monkey Threat Detection and Alert System.

The system detects monkeys in video footage and is trained using a custom dataset from Roboflow. Training and testing are done in Google Colab, with data stored in Google Drive.


### ⛰️ How It Started

My college is based in the **Shimla-Solan hills**, where **wildlife nests among us** — more of a **cohabiting situation**.  
But **cohabiting can turn feral real quick**.

**Monkeys** roam our college grounds and enter hostels, waiting to **pounce on anything remotely edible** — regardless of whether it’s in **our hands or halfway in our mouths**.  
They **topple dustbins**, **wait outside rooms** — basically creating an **unhygienic and anxiety-inducing** situation.

One such day, while we were on a **deadline** to come up with ideas for our minor projects, I opened the door to find a **small primate staring directly into my eyes**, calmly sitting at my doorstep.  
And in that moment, my **heart decided it needed to come up with something fast** — before it **gave out from the daily jump-scares** these monkeys kept serving.


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
