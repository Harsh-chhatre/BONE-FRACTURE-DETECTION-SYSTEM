# Bone Fracture Detection  

## 📌 Dataset  
For dataset go to this link:  
👉 [GRAZPEDWRI-DX Dataset](https://www.kaggle.com/datasets/jasonroggy/grazpedwri-dx)  

## ⚡ YOLOv7  
For YOLOv7 go to this link:  
👉 [YOLOv7 Repository](https://github.com/WongKinYiu/yolov7)  

---

## 🔄 Dataset Preparation  
Use `split.py` to split the dataset into **train**, **valid**, and **test** sets.  

---

## 📂 Dataset Structure  

```bash
└── GRAZPEDWRI-DX_dataset     
     ├── yolov5
     │    ├── images
     │    └── labels
     │
     ├── images
     │    ├── train
     │    │    ├── train_img1.png
     │    │    └── ...
     │    ├── valid
     │    │    ├── valid_img1.png
     │    │    └── ...
     │    └── test
     │         ├── test_img1.png
     │         └── ...
     │
     └── labels
          ├── train
          │    ├── train_annotation1.txt
          │    └── ...
          ├── valid
          │    ├── valid_annotation1.txt
          │    └── ...
          └── test
               ├── test_annotation1.txt
               └── ...

