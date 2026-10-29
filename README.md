# cv-lab

Computer vision lab experiments in Python using OpenCV, NumPy and Matplotlib.

| # | Topic | Notebook |
|---|-------|----------|
| 1 | Reading, inspecting and transforming images | `exp-01.ipynb` |
| 2 | Salt and pepper noise | `exp-02.ipynb` |
| 3 | Median filter - kernel size and stride | `exp-03.ipynb` |
| 4 | Gaussian noise and Gaussian smoothing | `exp-04.ipynb` |
| 5 | Edge detection with the Sobel operator | `exp-05.ipynb` |
| 6 | Thresholding with Otsu's method | `exp-06.ipynb` |
| 7 | Texture analysis using GLCM | `exp-07.ipynb` |
| 8 | Detecting three straight lines with the Hough transform | `exp-08.ipynb` |

## Setup

```bash
pip install -r requirements.txt
jupyter notebook
```

The notebooks use sample images that ship with scikit-image (or a synthetic image in exp 8), so no extra data download is needed.
