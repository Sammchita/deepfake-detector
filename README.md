# DeepScan
DeepScan is a Flask-based web application that detects manipulated images and videos using deep learning. 
It combines AI classification with digital forensic analysis to help users identify
potential deepfakes through confidence scores, heatmaps, and forensic reports.

## Project Preview
1. Home Page
<img width="903" height="508" alt="image" src="https://github.com/user-attachments/assets/6f5a357e-ffaa-45b5-8b7e-91d844c776ad" />

2. File Upload Interface
<img width="903" height="508" alt="image" src="https://github.com/user-attachments/assets/f3f47819-b03f-422a-9781-cdf54baf756a" />

3. Cropped Face Detected by the System
<img width="903" height="515" alt="image" src="https://github.com/user-attachments/assets/ba90331c-87ec-40e2-8a39-4e9ef400ec40" />

4. Heatmap Visualization
   <img width="903" height="478" alt="image" src="https://github.com/user-attachments/assets/32f330ee-4228-447e-85f6-e37e91122f48" />
   
5. : Detection Summary Report
   <img width="903" height="459" alt="image" src="https://github.com/user-attachments/assets/a4a46f19-0de8-485b-a3c0-88e9eac8a153" />
   
6. Error Message Displayed When No File Is Selected
  <img width="903" height="471" alt="image" src="https://github.com/user-attachments/assets/de35bb33-0197-4a38-b98c-34e09a11dcfa" />

7. Video Detection Result Interface 
   <img width="903" height="459" alt="image" src="https://github.com/user-attachments/assets/e20b19e4-d889-41ec-ac48-df60c08c6f12" />

## Features

### Image Deepfake Detection
Detects manipulated facial images using a trained CNN model.

### Video Deepfake Detection
Extracts video frames and predicts authenticity through majority voting.

### Face Detection
Automatically locates faces before prediction.

### AI Attention Heatmap
Highlights image regions influencing the model's prediction.

### Image Quality Analysis
Measures image sharpness, compression artifacts, and resolution.

### Consistency Analysis
Detects inconsistencies commonly found in AI-generated media.

### Risk Level Estimation
Assigns Low, Medium, or High risk based on confidence.

### Confidence Score
Displays prediction confidence percentage.

### Forensic Report
Generates a detailed analysis report summarizing all findings.

### Responsive Interface
Accessible from desktop, tablet, and mobile devices.


## System Architecture

<img width="614" height="225" alt="image" src="https://github.com/user-attachments/assets/362d9cd0-90d9-49dd-9dcc-d1e87a24f19e" />

## Tech Stack

- Python
- Flask
- TensorFlow / Keras
- OpenCV
- NumPy
- HTML
- CSS

## How it Works

1. User uploads an image or video.
2. Faces are detected using OpenCV.
3. The trained CNN predicts whether the face is Real or Fake.
4. Forensic analyses are generated.
5. A detailed AI report is displayed.

   
## Future Improvements

- Grad-CAM attention maps
- Better deepfake model
- REST API
- Multiple-face detection
- Live webcam analysis

## Contributors
  
  - Tina Nachiring Rai
  - Samchita Pandey
  -  Aayusha Khatiwada

  ## License

This project is developed for educational purposes as a final-year academic project.
