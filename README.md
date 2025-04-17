# Human Recognition Project
![download](https://github.com/user-attachments/assets/ad7bf1b0-f102-4db3-becc-08a7a79c107b)

This is a Streamlit-based web application that uses the DeepFace library to analyze and recognize human emotions from images and videos.

## Features

- **Image Emotion Recognition**: Upload an image, and the app will detect and display the dominant emotion.
- **Video Emotion Recognition**: Upload a video, and the app will analyze frames to detect emotions in real-time.

## Installation

1. Clone the repository:
  ```bash
  git clone https://github.com/sammaemad/Human_Emotion_Recognation.git
  ```
2. Create a virtual environment:
  ```bash
  python -m venv .venv
  ```
3. Activate the virtual environment:
  - On Windows:
    ```bash
    .venv\Scripts\activate
    ```
  - On macOS/Linux:
    ```bash
    source .venv/bin/activate
    ```
4. Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
5. Install the deepface library (if not already installed):

 ```bash
  pip install deepface
  ```


## Usage

1. Run the application:
```bash
streamlit run human_emotions_rec.py
```

2. Choose between "Image" or "Video" mode:

      - Image: Upload an image file (.jpg, .png, .jpeg).
      - Video: Upload a video file (.mp4, .mov, .avi).
3. View the detected emotion(s) displayed on the app.

## File Structure
- human_emotion.ipynb: Jupyter Notebook for development and testing.
- human_emotions_rec.py: Main Python script for the Streamlit app.
- requirements.txt: List of dependencies for the project.


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- DeepFace for emotion analysis.
- Streamlit for building the web app.


