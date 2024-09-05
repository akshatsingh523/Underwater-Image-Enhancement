

---

# **Underwater-Image-Enhancement with SwarmGen**

## Project Overview

**Underwater-Image-Enhancement with SwarmGen** focuses on improving the quality of underwater images, which are often degraded by the dominance of blue and green wavelengths and scattering effects. These factors lead to poor image usability in applications such as marine research, underwater archaeology, and surveillance. This project leverages Particle Swarm Optimization (PSO), a nature-inspired algorithm, to enhance underwater images and improve their suitability for analysis and interpretation.

## Problem Statement

Underwater images suffer from poor quality due to scattering and color imbalance caused by the dominance of blue and green wavelengths. These distortions hinder their usability for image-based tasks, requiring enhancement to ensure accurate analysis.

## Use Case

Improving the quality of underwater images is critical for accurate analysis in a variety of fields, such as:
- Marine research
- Underwater archaeology
- Environmental monitoring
- Underwater surveillance

## Data Collection

The dataset for this project was collected from diverse aquatic environments, including oceans, lakes, and rivers. The images captured a range of underwater scenarios with varying visibility and lighting conditions, providing a comprehensive dataset for testing enhancement algorithms.

## Data Preprocessing

To address common underwater image issues, the following preprocessing techniques were applied:
- **Gaussian Blur**: Used to reduce image noise and scattering effects.
- **Histogram Equalization**: Applied to enhance image contrast and mitigate the dominance of blue and green wavelengths.

## Model Implementation

To further enhance the preprocessed images, **Particle Swarm Optimization (PSO)** was implemented. PSO is inspired by the collective behavior of flocks of birds or schools of fish and was particularly effective in optimizing image quality for underwater scenarios.

### PSO Features:
- Adaptive optimization based on nature-inspired behavior.
- Effective for enhancing image quality metrics, such as contrast and color balance.
  
## Results

The image enhancement results were evaluated using several image quality metrics, showing significant improvements:

- **Entropy**: Improved from 6.055 to 7.21
- **Contrast**: Enhanced from 17.78 to 47.51
- **Color Contrast Index (CCI)**: Increased from 0.035 to 0.038
- **Image Quality Index (IQI)**: Enhanced from 3.0018 to 16.21

### Comparison to Other Methods:
- **Histogram Equalization (HE)**: Contrast improved from 7.77 to 73.75
- **Iterative Color Management (ICM)**: CCI increased from 0.041 to 0.041
- **Recursive Global Histogram Stretching (RGHS)**: Contrast improved from 7.61 to 62.91
- **Underwater Color Correction Model (UCM)**: CCI increased from 0.043 to 0.043
- **Rayleigh Distribution**: Contrast improved from 7.55 to 75.26

These results demonstrate that the **SwarmGen** approach using PSO is effective for underwater image enhancement, yielding superior contrast and overall image quality compared to traditional methods.

---
