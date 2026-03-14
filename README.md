# Automatic Number Plate Recognition using YOLOv8

This project detects vehicles and extracts license plate numbers from video using YOLOv8 and OCR.  
It identifies vehicles, detects license plates, and recognizes the text from the plate.

## Demo
https://drive.google.com/file/d/1hyNEF3CqWqLlbB5xK01TiGRQE8dAZw-P/view?usp=sharing

## Features
- Vehicle detection using YOLOv8
- License plate detection
- Optical Character Recognition (OCR) for plate text
- Vehicle tracking using SORT algorithm
- Smooth visualization of detection results

## Tech Stack
- Python
- OpenCV
- YOLOv8
- EasyOCR / Tesseract OCR
- SORT tracking algorithm

## Installation

1. Clone the repository
git clone https://github.com/Rammanideep-ghantasala/Automatic-Number-Plate-Recognition-YOLOv8.git

2. Navigate to the project folder
cd Automatic-Number-Plate-Recognition-YOLOv8

3. Install dependencies
pip install -r requirements.txt

4. Run the project
python main.py


---

## 6️⃣ Dataset
```markdown
## Dataset
License plate dataset from Roboflow.

## Output
The system generates a CSV file containing detected license plate numbers and timestamps.