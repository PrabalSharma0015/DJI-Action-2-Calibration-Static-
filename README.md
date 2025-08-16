# 🎥 DJI Action 2 Camera Calibration (Static)

This repository contains my work on **camera calibration** using the **DJI Action 2** with **static chessboard images**, implemented in **OpenCV**.  

## 🔧 What’s Inside
- Captured multiple chessboard images from the DJI Action 2.  
- Detected calibration pattern corners using OpenCV.  
- Computed:  
  - **Camera Matrix (Intrinsic Parameters)**  
  - **Distortion Coefficients**  
  - **Focal Lengths**  
- Compared my results with **DJI’s official camera specifications**.  
- Learned why calibration outputs may slightly differ due to:  
  - Sensor assumptions  
  - Field of View (FoV)  
  - Lens distortions  

## 📌 Why It Matters
Accurate camera calibration is the **foundation of AR/VR, robotics, simulations, and computer vision tasks**. This exercise gave me practical insight into how real-world hardware connects with vision algorithms.  

## 🚀 How to Use
1. Clone the repo or open the Jupyter/Colab notebook.  
2. Run the cells step by step.  
3. Upload your own chessboard images (or use the sample dataset).  
4. View calibration results and compare with manufacturer values.  

## 📊 Results (Sample)
| Parameter               | Calculated (from OpenCV) | Manufacturer Specs |  
|--------------------------|--------------------------|---------------------|  
| Focal Length (fx, fy)   | ~X.XX, ~Y.YY             | Official DJI Value |  
| Principal Point (cx, cy)| ~X.XX, ~Y.YY             | Official DJI Value |  
| Distortion Coefficients | [k1, k2, p1, p2, k3]     | N/A (not provided) |  

*(Values are approximate and depend on dataset used)*  

## 🙏 Acknowledgement
A big thanks to my mentor **Dr. Piyush Singh** for his guidance and motivation throughout this learning journey.
