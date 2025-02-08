# **Call-to-Text Spam Detection System**

## **Project Description**
The **Redmi Spam Detection Project** is a robust speech-to-text system that identifies spam content by analyzing audio inputs. This solution is ideal for applications requiring audio transcription and text-based spam detection, such as customer service monitoring and secure communication systems.

---

## **Features**
- 🎤 **Speech-to-Text Conversion:** Converts audio input to text using Google's Speech Recognition API.
- 🔍 **Spam Detection:** Identifies spam keywords such as "free," "offer," "urgent," and more.
- 📂 **Transcription Storage:** Saves transcription data to text files for analysis.
- 📜 **Spam Word Reporting:** Generates and stores a report of detected spam words.
- 🌐 **User-Friendly Web Interface:** Displays results through a clean web interface.

---

## **How It Works**
1. **Audio Recording:** The user speaks into the microphone to capture audio.
2. **Transcription:** The system converts speech to text and saves the transcription.
3. **Spam Detection:** The text is scanned for predefined spam keywords.
4. **Result Presentation:** Detected spam words are displayed and saved for review.

---

## **Tech Stack**
- **Backend:** Django & Flask
- **Speech Processing:** `speech_recognition` Library
- **Frontend:** HTML/CSS Templates
- **Programming Language:** Python

---

## **Installation Instructions**
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/your-username/redmi-spam-detection.git
   cd redmi-spam-detection
