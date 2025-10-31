# 🧠 Image Processing Techniques – Beshoy William

This repository contains a collection of **image processing experiments** implemented using **Python, OpenCV, and NumPy**.  
Each section demonstrates a specific concept in digital image processing — from basic pixel manipulation to advanced frequency-domain filtering.

---

## 📂 Project Structure

| Section | Description |
|----------|--------------|
| **1. Import & Display** | Reading, displaying, and normalizing grayscale images. |
| **2. Pixel Manipulation** | Modifying image pixels using loops and conditions. |
| **3. Negative Transformation** | Generating a negative image using pixel inversion. |
| **4. Power-Law & Log Transformations** | Applying non-linear intensity transformations. |
| **5. Min, Max & Median Filters** | Noise reduction using basic neighborhood filters. |
| **6. Spatial Filters** | Implementations of Average, Sobel, Prewitt, and Laplacian filters. |
| **7. Thresholding & Segmentation** | Single and multi-level thresholding for image segmentation. |
| **8. Contrast Stretching** | Enhancing contrast using intensity range adjustment. |
| **9. Histogram Equalization** | Normalizing image brightness distribution. |
| **10. Image Resizing** | Downsampling image resolution manually. |
| **11. Fourier Transformations** | Frequency-domain filtering using LPF, HPF, Sobel, and Laplacian filters. |

---

## ⚙️ Technologies Used
- **Python 3.8+**
- **OpenCV (cv2)**
- **NumPy**
- **Matplotlib**

---

## 🧩 Key Concepts Demonstrated

### 🖼️ Image Normalization
```python
img = ocv.imread("Y16.jpg", 0)
img = img / 255
```

### 🌗 Negative Transformation
```python
img[row][col] = 255 - img[row][col]
```

### ⚡ Power Law (Gamma Correction)
```python
img[row][col] = 6 * (img[row][col]) ** 2
```

### 🧮 Log Transformation
```python
img[row][col] = 8 * np.log2(img[row][col])
```

### 🧊 Filtering Techniques
- **Average Filter:** smooths images and reduces noise.
- **Median Filter:** preserves edges while removing salt-and-pepper noise.
- **Sobel & Prewitt:** detect edges by computing image gradients.
- **Laplacian:** highlights regions of rapid intensity change.

### 🎭 Thresholding & Segmentation
Separates objects from the background using intensity-based thresholds.

### 📊 Histogram Equalization
Balances brightness levels across the image to enhance contrast.

### 🔄 Fourier Transform (Frequency Domain)
Implements:
- **LPF (Low-Pass Filter):** for smoothing.
- **HPF (High-Pass Filter):** for sharpening.
- **Frequency-domain Sobel and Laplacian filters.**

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/image-processing-lab.git
   cd image-processing-lab
   ```

2. Install dependencies:
   ```bash
   pip install opencv-python numpy matplotlib
   ```

3. Run any section file (e.g., Negative Image):
   ```bash
   python negative_image.py
   ```

---

## 🧾 Author

**Beshoy William**
*Image Processing Section – Course Project*  

Prepared and implemented by:  
**Beshoy William**  
Software Developer | Image Processing Enthusiast  
