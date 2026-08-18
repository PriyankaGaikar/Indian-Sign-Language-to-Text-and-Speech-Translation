Indian Sign Language to Text and Speech Translation

📌 Project Overview
Indian Sign Language to Text and Speech Translation is a computer vision and machine learning-based system designed to recognize Indian Sign Language (ISL) hand gestures and convert them into text and speech.

The system uses MediaPipe to detect and extract hand landmarks from a live webcam feed and a TensorFlow/Keras model to classify the detected gestures. The recognized signs are displayed as text and can also be converted into speech, helping improve communication between people who use Indian Sign Language and those who may not understand it.

The project supports recognition of English alphabet gestures and numerical digits, with additional multilingual text-to-speech support for Hindi and Marathi.

🎯 Objectives
To develop a real-time Indian Sign Language recognition system.
To detect and track hand gestures using computer vision.
To classify ISL gestures using a machine learning model.
To convert recognized gestures into meaningful text.
To convert the generated text into speech.
To provide multilingual speech output in Hindi, Marathi, and English.
To create a simple and user-friendly interface for real-time interaction.

✨ Features
🖐️ Real-time hand gesture recognition
🔤 Alphabet gesture recognition
🔢 Digit recognition (0–9)
📷 Webcam-based gesture detection
📝 Conversion of gestures into text
🔊 Text-to-speech conversion
🌐 Multilingual support
🇮🇳 Hindi and Marathi language support
🖥️ Graphical User Interface
⚡ Real-time prediction using computer vision and machine learning

🛠️ Technologies Used
Programming Language
Python
Machine Learning & Computer Vision
TensorFlow
Keras
OpenCV
MediaPipe
NumPy
Pandas
Scikit-learn
GUI & Speech
Tkinter
gTTS (Google Text-to-Speech)
pyttsx3
Development Tools
Jupyter Notebook
VS Code
Git & GitHub

🔄 System Workflow
The system follows the following workflow:

Webcam
   ↓
Hand Detection
   ↓
Hand Landmark Extraction
   ↓
Preprocessing
   ↓
Trained ML Model
   ↓
Gesture Classification
   ↓
Recognized Text
   ↓
Text-to-Speech
   ↓
Audio Output

1. Hand Detection

The webcam captures the user's hand gestures in real time. MediaPipe Hands is used to detect the hand and identify its landmarks.

2. Landmark Extraction

The system extracts the coordinates of the detected hand landmarks and uses them as input features for gesture classification.

3. Gesture Classification

The extracted features are passed to a trained TensorFlow/Keras model, which predicts the corresponding ISL gesture.

4. Text Generation

The predicted gesture is converted into its corresponding alphabet or digit and displayed as text.

5. Speech Generation

The recognized text can be converted into speech using text-to-speech libraries, enabling audio-based communication.

🔤 Supported Gestures

The system is designed to recognize:

English Alphabet: A–Z
Digits: 0–9

The recognition system can be further expanded to support additional ISL signs and complete words or sentences.

🌐 Multilingual Support

The system provides multilingual text-to-speech functionality and can generate speech in:

🇬🇧 English
🇮🇳 Hindi
🇮🇳 Marathi

This feature makes the system more useful in multilingual environments.

📊 Performance

The model achieved an average prediction accuracy of approximately 92% across the tested alphabet gestures.

During testing, 23 out of 25 tested alphabet gestures were correctly recognized under the evaluation conditions.

Note: Recognition performance may vary depending on lighting conditions, hand orientation, camera quality, background, and distance from the camera.

💻 Installation

Prerequisites
Make sure you have:
Python 3.x
Webcam
Windows/Linux/macOS
Required Python libraries

Clone the Repository
git clone https://github.com/PriyankaGaikar/Indian-Sign-Language-to-Text-and-Speech-Translation.git

Navigate to the Project
cd Indian-Sign-Language-to-Text-and-Speech-Translation

Create a Virtual Environment
python -m venv env

Activate the Virtual Environment
For Windows:
env\Scripts\activate
Install Dependencies
pip install -r requirements.txt

▶️ How to Run
After installing the required dependencies, run the main Python application:
python main.py
Replace main.py with the actual entry-point filename if your project uses a different file.

📁 Project Structure
Indian-Sign-Language-to-Text-and-Speech-Translation/
│
├── dataset/
├── model/
├── src/
├── main.py
├── requirements.txt
├── README.md
└── .gitignore

The actual folder structure may vary depending on the project implementation.

🔮 Future Scope

The project can be further improved by:

Improving recognition accuracy under different lighting conditions.
Supporting dynamic hand gestures and continuous signs.
Recognizing complete words and sentences.
Expanding the ISL gesture vocabulary.
Improving multilingual support.
Developing a mobile application.
Developing a web-based version.
Implementing more advanced deep learning architectures.
Improving real-time prediction speed and robustness.

🎓 Project Type

Final Year Engineering Project

Domain:
Computer Vision | Machine Learning | Artificial Intelligence | Natural Language & Speech

👩‍💻 Author

Priyanka Madhavrao Gaikar

B.E. Computer Engineering

📄 Disclaimer

This project was developed as an academic/final-year project for educational and research purposes. The system is intended to demonstrate the application of computer vision and machine learning techniques for Indian Sign Language recognition.