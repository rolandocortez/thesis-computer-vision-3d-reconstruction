# Computer Vision System for Object Detection, Classification, Localization, and Partial 3D Reconstruction

This repository presents the structure of my undergraduate thesis in Electronics Engineering at **Universidad Simón Bolívar**, focused on **Computer Vision, Depth Estimation, and 3D Reconstruction**.

The thesis received an *Outstanding Mention* from the IEEE Ambassador for Venezuela, who described it as “at a postgraduate level.”  
The full document is currently under academic review; therefore, only the index is publicly shared here.

---

## Table of Contents

### Abstract  
### Acknowledgments  
### List of Tables  
### List of Figures  

---

## Chapter 1: Introduction  
- Motivation  
- Objectives  
  - General Objective  
  - Specific Objectives  
- Structure  

---

## Chapter 2: Fundamentals of Computer Vision and Camera Models  
- Definition of a Digital Image  
- Image Formation: The Pinhole Principle  
- Pinhole Camera Model and Perspective Projection  
- Coordinate Systems: Image, Camera, and World  
- Camera Lens and Types of Distortion  

---

## Chapter 3: Camera Calibration  
- Homogeneous Coordinates and Linear Camera Model  
- Types of Calibration  
- Direct Linear Transformation (DLT) Method  
- Homography  
- Zhang Method  
- Technical Specifications of the Camera Used  
- Chessboard Calibration  
  - Calibration Results with Chessboard  
- ArUco Markers and ChArUco Calibration  
  - Definition  
  - Marker Creation and Detection  
  - ChArUco Boards  
  - Calibration Results with ChArUco  
- Pattern Comparison  
- Calibration Evaluation Experiment  

---

## Chapter 4: Detection and Classification  
- Neural Networks  
  - Linear Regression  
  - The Perceptron  
  - The Multilayer Perceptron (MLP)  
- Convolutional Neural Networks (CNNs)  
  - Classical Filters in Image Processing  
  - Basic CNN Architecture  
  - Comparison Between Classical and Learned Filters  
- You Only Look Once (YOLO) Model  
  - General Description  
  - Training Phase  
  - Inference Phase  
- Training with Roboflow Dataset and YOLOv10 for Object Detection  

---

## Chapter 5: Techniques for Estimating Scene Depth  
- Active Techniques  
  - Structured Light  
  - Photometric Stereo  
  - Time of Flight (ToF)  
  - LED Line Scanner (Laser Scanner)  
- Passive Techniques  
  - Neural Networks  
  - Depth from Defocus  
  - Shape from Shadows  
  - Shape from Specularities  
  - Shape from Texture  
  - Shape from Silhouettes  
  - Stereo Vision  
  - Structure from Motion  
- Technique Selection Process for the Project  
  - Emulated Stereo Vision  

---

## Chapter 6: Own Implementation – Conversion of Relative to Absolute Depth Maps with Reference Markers (CRA2M)  
- Overview of MiDaS Functioning  
  - Datasets Used for Training and Evaluation  
  - MiDaS Limitations  
  - Introduction to Transformer Technology  
  - Using Transformers to Improve MiDaS  
  - Version Comparisons  
- CRA2M Explanation  
  - Obtaining the Relative Depth Map  
  - ArUco Marker Detection and Translation Vector Extraction  
  - Extracting the Marker’s Relative Depth Value from the Depth Map  
  - Scale Factor Calculation  
  - Applying the Scale Factor to the Depth Map  
- Results  
  - Homogeneous Background  
  - Non-homogeneous Background  
  - Multiple Iterations for Averaging Results  
  - Using Chessboard Pattern for Reference Distance  
  - Processing Time Difference Between ArUco and Chessboard Methods  
  - Lighting Impact on ArUco Detection  
  - Conclusions and Optimization Recommendations  

---

## Chapter 7: Structured Light with Projector-Camera System  
- Evolution Toward Gray-Code Structured Light  
  - Depth Estimation Using a Laser Pointer  
  - Depth Estimation Using a Light Stripe  
  - Depth Estimation with Multiple Light Stripes  
  - Binary-coded Structured Light  
- Structured Light with Gray Coding  
- Pixel Classification and Direct/Indirect Light Separation  
  - Simplified Illumination Model  
  - Steps for Illumination Decomposition  
  - Difference Between Armstrong and Nayar Methods  
  - Formula for Determining the Number of Patterns to Use  
  - Xu and Aliaga Pixel Classification Rules  
- Stereo Calibration  
  - Epipolar Geometry  
  - Fundamental Matrix Calculation  
- Projector-Camera System Calibration  
- Triangulation  
- Technical Aspects of Projectors to Consider  
- Projection Technologies  
- Projector Technical Specifications  
- Results  
  - Pixel Encoding  
  - Pixel Decoding  

---

## Chapter 8: [Section Redacted – Under Review for Publication]  
> This chapter presents an **innovative 3D reconstruction method** currently under submission to the **International Conference on Automation, Robotics and Applications (ICARA 2026)**, Istanbul, Turkey.  

---

## Chapter 9: Conclusions and Future Work  
- General Conclusions  
- Future Research Directions  

---

## References  

---

## Technologies and Tools  
- Python, OpenCV, PyTorch  
- YOLOv10, MiDaS, Transformers  
- Camera Calibration (Zhang Method, DLT, Homographies)  
- Depth Estimation, Stereo Vision, Structure from Motion  
- 3D Reconstruction and Structured Light Systems  

---

## Note  
> This index is shared for academic and professional reference.  
> The detailed content of Chapter 8 remains confidential until the ongoing publication process is complete.
