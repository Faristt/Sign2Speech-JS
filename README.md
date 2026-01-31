An accessibility-focused web application designed to bridge communication gaps. Sign2Speech-JS translates hand signals into spoken words in real-time, specifically developed as an AI detection project to assist individuals with speech impairments.

🛠 Tech Stack
Core Logic: JavaScript (ES6+)

AI Framework: TensorFlow.js

Model Host: Google Teachable Machine

Voice Engine: Web Speech API (SpeechSynthesis)

Styling: CSS3 with a focus on modern, dark-mode dashboards

✨ Key Features
Real-time Hand Detection: Leverages a custom-trained image classification model to recognize sign language gestures via webcam.

Intelligent Word Builder: Features a confirmation logic where a user holds a sign for ~1.5 seconds to "lock in" a letter, preventing accidental inputs.

Audio Feedback: Includes a "Speak" function that utilizes Text-to-Speech (TTS) to read out the completed words or individual letters.

Visual UX: Provides immediate visual feedback through confidence bars and UI scaling when a letter is successfully registered.

📖 How It Works
The system utilizes an alphabetMap to translate specific model classes into the English alphabet:

Gesture Recognition: The AI identifies classes (e.g., Class 1 maps to A, Class 2 maps to B).

Confidence Threshold: Only predictions with a confidence score higher than 90% are considered for the word builder.

Word Management: Users can delete the last letter (Backspace) or clear the entire string once the message is complete.

🚀 Getting Started
Clone the repository.

Open test.html in any modern web browser (Chrome/Edge recommended for Web Speech support).

Click "LAUNCH CAMERA" and grant camera permissions.

Position your hand within the frame to start translating.

🎓 Academic Context
This project was developed at UTeM (Universiti Teknikal Malaysia Melaka).

Developer: FARIS HADIF BIN MOHD FAISAL

Student ID: D132510136
