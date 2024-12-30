# 🎯 Gesture Calculator using AI and Computer Vision

This project is a **Gesture Calculator** that uses **AI** and **Computer Vision** to recognize hand gestures and solve mathematical problems in real time. The system captures hand movements through a webcam, interprets gestures as mathematical inputs, and computes results using AI.

<center> <img src = "https://github.com/sandipanrakshit34/Guestures-Calculator-using-AI-and-Computer-vision/blob/main/Screenshot-2023-09-21-110656.png" width = 100%>

## 📝 Features
- **Hand Gesture Recognition**: Detects hand gestures to input mathematical symbols and equations.
- **Real-time Calculation**: Processes and solves math problems in real-time based on gestures.
- **AI-Powered**: Uses Google’s Generative AI to handle math problem solving.
- **Web-based Interface**: Built with **Streamlit** for an interactive experience.

## Access
Deployed **App** => https://huggingface.co/spaces/sandipan23/NeuraCalc

## 💡 How It Works
1. **Hand Detection**: Using **OpenCV** and **cvzone**, the system tracks hand movements through the webcam.
2. **Gesture Recognition**: Specific gestures represent mathematical inputs (e.g., numbers, operators).
3. **AI Computation**: When the gesture input is complete, it is sent to **Google Generative AI** for solving.
4. **Real-time Output**: The solution is displayed instantly.

## 🔧 Tech Stack
- **Python**
- **OpenCV** for computer vision tasks
- **cvzone** for hand tracking
- **Google Generative AI** (gemini-1.5-flash)
- **Streamlit** for the web interface
- **Pillow** for image processing

## 🚀 Getting Started


## Author

- [@sandipanrakshit34](https://github.com/sandipanrakshit34)

##

### Prerequisites
Before running the project, ensure the following dependencies are installed:
- Python 3.8+
- OpenCV
- cvzone
- google-generativeai
- Streamlit
- Pillow

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/sandipanrakshit34/Guestures-Calculator-using-AI-and-Computer-vision.git
    cd gesture-calculator
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Application**:
    ```bash
    streamlit run app.py
    ```

4. **Webcam Setup**:
   Ensure your webcam is properly connected and working to capture hand gestures.
