# 📚 EC7212 – Computer Vision and Image Processing TakeHome 2

## 👤 Details
- **Name:** EG/2020/4330
- **Name:** Sheshan K.H.N
- **Course:** EC7212 – Computer Vision and Image Processing
- **Assignment:** TakeHome 2

## 📝 Assignment Tasks

### Task 1
- Consider an image with 2 objects and a total of 3-pixel values (1 for each object and one for the background). Add Gaussian noise to the image. Implement and test Otsu’s algorithm with this image. 

### Task 2
- Implement a region-growing technique for image segmentation. The basic idea is to start from a set of points inside the object of interest (foreground), denoted as seeds, and recursively add neighboring pixels as long as they are in a pre-defined range of the pixel values of the seeds.  

---

## 📁 Folder Structure

```
│
├── task 1/
│   ├── output_images      # Result Images and Syntetic Image
│   └── Q1.ipynb           # Script for Task 1
├── task 2/
│   └── output_images      # Results
│   └── Q2.ipynb           # Script for Task 2
│   └── image_02.jpg       # Original image for the task 2
└── README.md
```

---

## 🛠️ Libraries Used

- os  
- numpy  
- matplotlib.pyplot  
- cv2  
- skimage.util.random_noise  
- skimage.filters.threshold_otsu  
- collections.deque  


