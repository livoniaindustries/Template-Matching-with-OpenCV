# Template Matching with OpenCV (Python)

This project demonstrates **single template matching using OpenCV** in Python.  
The script detects the location of a template image inside a larger image using OpenCV’s `matchTemplate` function and draws a bounding box around the detected region.

---

## Installation

### 1. Create Virtual Environment

```bash
python -m venv venv
```
2. Activate Virtual Environment
```
```
Windows
```
venv\Scripts\activate
```
Mac / Linux
```
source venv/bin/activate
```
3. Install Dependencies
 ```
pip install opencv-python
pip install numpy
pip install imutils
```
Usage
```
python single_template_matching.py --image images/coke_bottle.png --template images/coke_logo.png
