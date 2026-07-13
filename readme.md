# Face Detection using SCRFD

## Description
This project detects human faces in any uploaded image using 
the pretrained SCRFD model via InsightFace library.
For each detected face, the model outputs:
- Bounding box (location of face)
- Facial landmarks (eyes, nose, mouth corners)
- Confidence score (how sure the model is)

## Model
- **SCRFD** (Sample and Computation Redistribution for Efficient Face Detection)
- Pretrained model: `buffalo_l` via InsightFace
- Trained on millions of face images
- No training required — ready to use immediately

## Tech Stack
- Python
- OpenCV
- InsightFace
- ONNX Runtime
- Matplotlib
- Google Colab

## How to Run
1. Open the notebook in Google Colab
2. Run all cells in order
3. Upload any image when prompted
4. View detected faces with bounding boxes and landmarks

## Results
- Detects multiple faces in one image
- Draws green bounding boxes around each face
- Marks 5 facial landmarks (red dots)
- Shows confidence score per face
<img width="866" height="668" alt="image" src="https://github.com/user-attachments/assets/29009a50-4fbe-4b84-8de3-9c0b1309c454" />

## Pipeline Stage
This project implements **Stage 3** of the Bengali Celebrity 
Multimodal Dataset pipeline:
