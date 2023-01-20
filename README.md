# pothole-classification
Pothole classification solution for detecting and identifying potholes.

Steps for usage:

1. Clone the repo using the following command:

git clone https://github.com/nachi-hebbar/pothole-classification

2. Install dependencies using the following command:

pip install -r requirements.txt

3. Run the following command to run inference of the object detection model. Provide the video path after the source argument:

python detect.py --source "path/to/source" --weights pothole_detector.pt
