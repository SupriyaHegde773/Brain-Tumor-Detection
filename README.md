# Brain Tumor Detection Using Machine Learning

## Overview
This project is a **Brain Tumor Detection System** that uses **Machine Learning (SVM)** to classify brain MRI images as either **No Tumor** or **Positive Tumor**. The application is built using **PyQt5** for GUI and **OpenCV** for image processing.

## Features
- **Load MRI Scans** for analysis
- **Predict Brain Tumor** using an SVM model
- **Highlight Tumor Area** in detected images
- **User-friendly GUI** using PyQt5
- **Real-time image processing** with OpenCV

## Technologies Used
- **Python 3.x**
- **PyQt5** (GUI framework)
- **OpenCV** (Image processing)
- **Scikit-learn** (Machine learning)
- **Matplotlib** (Visualization)
- **NumPy & Pandas** (Data handling)

## Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/Brain-Tumor-Detection.git
   cd Brain-Tumor-Detection
   ```

2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```sh
   python main.py
   ```

## Usage
- Click **'Load Image'** to upload an MRI scan.
- Click **'Predict'** to detect whether a tumor is present.
- If a tumor is detected, the system will **highlight** the affected area.

## Deployment Guide

### Option 1: Run Locally
Simply execute the **main.py** file:
```sh
python main.py
```

### Option 2: Deploy Using Flask (Optional)
To expose the model as a web API:
1. Install Flask:
   ```sh
   pip install flask
   ```
2. Run the Flask API:
   ```sh
   python api.py
   ```
3. Use Postman or a frontend to send MRI images for classification.

### Option 3: Deploy on **Heroku/Streamlit**
For deploying as a **web application**, create a `Procfile` and use **Heroku** or **Streamlit**.


## License
This project is open-source and available under the **MIT License**.

---
### **GitHub Repository**
[https://github.com/your-username/Brain-Tumor-Detection](https://github.com/your-username/Brain-Tumor-Detection)

