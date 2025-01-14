### Data-Driven Fluid Mechanics Project

This repository contains a Python project that leverages image processing and Proper Orthogonal Decomposition (POD) to analyze fluid dynamics from video data. The project encompasses steps for extracting frames, adding noise, applying noise reduction techniques, and analyzing fluid flow using POD.

---

### Project Overview

The goal of this project is to derive meaningful insights from video frames of fluid dynamics experiments. The main objectives are:

- Extracting frames from video data.
- Simulating various experimental conditions by adding Gaussian and Speckle noise.
- Applying noise reduction techniques such as Gaussian blur and Non-Local Means (NLM) denoising.
- Analyzing fluid flow using Proper Orthogonal Decomposition (POD) to identify dominant flow modes.

---

### Installation and Setup

#### Prerequisites
Ensure you have Python 3.x installed along with the following Python libraries:

- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

#### Installation Instructions
Clone the repository to your local machine:

```bash
git clone https://github.com/ANKIT131103/Fluid-dynamics-using-machine-learning.git
```

---

### Dataset

Access the dataset used in this project via the following link:

[Dataset Link](https://drive.google.com/file/d/1WiSbCQmxu9ugEideLkcdAof1GA0uYXXT/view)

#### Data Overview

- **frames/**: Contains extracted frames from the original video.
- **noise_x/**: Directories (e.g., noise_20, noise_40) containing frames with added noise.
- **denoised_images_x/**: Contains frames after applying denoising techniques.

---

### Results

This section summarizes the effects of noise addition, noise reduction, and POD analysis on the fluid dynamics images. Below are key findings and visualizations demonstrating the project’s effectiveness.

#### Noise Addition Effects
Gaussian and Speckle noise were added to simulate various conditions. Key observations:

- **Gaussian Noise**: At levels of 20%, 40%, 60%, and 80%, images showed progressively obscured details and increased visual distortion.
- **Speckle Noise**: Introduced a grainy texture, reducing clarity and obscuring finer details.

#### Noise Reduction Techniques

Two noise reduction methods were applied to noisy images:

- **Gaussian Blur**: Reduced high-frequency noise effectively but caused a loss of edge details.
- **Non-Local Means (NLM) Denoising**: Superior at preserving edges and fine details while effectively reducing noise.

#### POD Analysis

POD was used to identify dominant flow modes in original, noisy, and denoised images. Key insights include:

- **Impact of Noise**: Noise significantly affected the accuracy of flow mode identification, introducing inconsistencies in lower energy modes.
- **Recovery with Denoising**: Post-denoising, flow modes closely resembled those from clean images, validating the efficacy of noise reduction methods.

---

