# Magic Gamma Telescope Classification

### **Problem Overview**:
The goal of this project is to classify high-energy particles as either **gamma** or **hadron** based on simulated data from a **ground-based atmospheric Cherenkov gamma telescope**. The dataset contains information about the Cherenkov photons recorded by the telescope's photomultiplier tubes, which is used to reconstruct the particle's characteristics.

### **Background**:
Cherenkov radiation is emitted when charged particles move faster than the speed of light in the atmosphere. This radiation is collected by photomultiplier tubes (PMTs) arranged in a camera plane. The data consists of the photon pulses captured by these PMTs, forming an image known as a **shower image**. Depending on the energy of the incoming gamma particle, the number of Cherenkov photons detected varies, typically ranging from a few hundred to several thousand.

- **Gamma Showers**: High-energy gamma rays produce electromagnetic showers in the atmosphere, leading to distinct patterns of Cherenkov radiation that can be detected and analyzed.
- **Hadronic Showers**: Cosmic rays interacting with the atmosphere produce hadronic showers, which have different patterns from gamma showers and are considered background noise in the data.

The challenge is to distinguish between these two types of showers based on the characteristics of the recorded images.

### **Machine Learning Challenge**:
Given the features extracted from these shower images, the task is to classify the particles into one of two categories:
- **Gamma**: The signal, representing high-energy gamma particles.
- **Hadron**: The background, representing hadronic showers from cosmic rays.

### **Approach**:
The project aims to develop and evaluate machine learning models that can predict the type of particle based on the features derived from the Cherenkov radiation patterns. Common models for this task include:
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**

### **License**:
This project is for educational and research purposes. Please refer to the project documentation and code for further details on usage rights.

### **Acknowledgments**:
The dataset was created by **P. Savicky**, Institute of Computer Science, AS of CR, Czech Republic.  
Hosted on the **UCI Machine Learning Repository**: [http://archive.ics.uci.edu/ml](http://archive.ics.uci.edu/ml).  


