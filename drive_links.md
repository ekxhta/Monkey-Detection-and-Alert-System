# Google Drive Resources

This project relies on Google Drive to store the dataset, trained model, and test video.



### Roboflow Monkey Detection Dataset

- Folder (contains `train/`, `test/`, `valid/`, `data.yaml`, and readme files):  
  → [Monkey Detection Dataset on Drive](https://drive.google.com/drive/folders/19lzEpqpo4mffK9B_YIv0OAGYLgrFy5Y1)
- The original dataset can also be downloaded from [Here](https://universe.roboflow.com/monkey-3byip/monkey-l6seo)

- Contents:
  - `train/`, `test/`, `valid/` – Images and YOLOv8 labels
  - `data.yaml` – For YOLOv8 dataset configuration
  - `readme.dataset.txt`, `readme.roboflow.txt` – Metadata & instructions



### Trained YOLOv8 Model Weights

- `best.pt` file (saved after training):  
  Located inside the dataset folder above



### Test Video for Inference

- Folder containing the test video used in inference:  
  [Test Video Folder on Drive](https://drive.google.com/drive/folders/1G7YEMr863kLuWCCuhp7C6iWxtDx6V652)



### Notes

- Make sure your Colab runtime has access to your Google Drive before running.
- Mount the drive using:
  ```python
  from google.colab import drive
  drive.mount('/content/drive')
