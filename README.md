# Static Camera Calibration (DJI Action 2)

## 📖 Overview
This project demonstrates **static camera calibration** using OpenCV on captured images from the DJI Action 2 camera.  
It estimates the intrinsic camera parameters and distortion coefficients using multiple chessboard images taken at different angles and positions.  

## ⚙️ Features
- Works with pre-captured images  
- Detects chessboard corners across multiple frames  
- Calculates intrinsic matrix and distortion coefficients  
- Undistorts images for accurate visual output  
- Reliable for fixed setups where camera position remains constant  

## 🚀 Why This Matters
Static calibration is ideal for applications where the camera setup does not change.  
It provides accurate distortion correction, crucial for **AR/VR, simulations, mapping, and photogrammetry**.  

## 🛠️ Technologies Used
- Python  
- OpenCV  
- Numpy  
- Jupyter/Google Colab  

## 📷 Workflow
1. Load chessboard images captured from DJI Action 2  
2. Detect chessboard corners across multiple images  
3. Compute camera intrinsic parameters & distortion coefficients  
4. Apply undistortion on test images  
5. Validate accuracy against real-world measurements  

## 🙏 Acknowledgment
Special thanks to **Dr. Piyush Singh** for his constant guidance and support in completing this work.  

---
#ComputerVision #OpenCV #AR #VR #Calibration #ImageProcessing #DJIAction2 #UnrealEngine
