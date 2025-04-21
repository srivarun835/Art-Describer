Project Title: Art Describer – Voice-Controlled Artwork Description System
Project Overview: Art Describer is a voice-interactive web application that uses advanced AI models to recognize and describe artworks or images. Designed to aid visually impaired users or provide interactive experiences in galleries or educational platforms, this system takes an image input (uploaded or captured), detects objects within it using YOLO, and generates a natural language description using BLIP (Bootstrapped Language Image Pretraining). Users can control the interaction and hear the output via voice commands and audio output, all powered through a Flask backend.
Key Technologies:
Flask – Web framework for backend routing and UI handling.
YOLO (You Only Look Once) – Real-time object detection model.
BLIP – Image captioning model to generate meaningful artwork descriptions.
SpeechRecognition – Enables voice command control.
pyttsx3 or gTTS – Converts generated text to speech.
Features:
Upload an image or capture it through webcam.
Automatically detects objects and generates captions.
Voice command interface to trigger actions like “describe this”, “repeat”, etc.
Audio feedback for descriptions, aiding accessibility.
 Installation Instructions:
1. Clone or unzip the project:
   unzip art-describer.zip
   cd art-describer
2.Create a virtual environment (optional but recommended):
  python -m venv venv
 source venv/bin/activate   # On Windows: venv\Scripts\activate
3. Install dependencies:
  pip install -r requirements.txt
If requirements.txt isn't provided, you can install manually:
 pip install flask torch torchvision torchaudio
 pip install speechrecognition pyttsx3
 pip install opencv-python
 To Run the Application:
  python app.py



  
   




