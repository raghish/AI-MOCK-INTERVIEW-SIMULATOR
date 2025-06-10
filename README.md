# AI-MOCK-INTERVIEW-SIMULATOR
How to Run the Project: AI Mock 
Interview Simulator 
1. Requirements 
   Ensure the following tools and libraries are installed: 
   System Requirements 
      - Python 3.8 or above 
      - OS: Windows, Linux, or macOS 
      - Microphone and audio input support 
    Python Dependencies 
    Install using pip: 
      pip install tkinter sounddevice pyttsx3 numpy vosk 
      gpt4all 
      *Note: tkinter comes pre-installed with most Python distributions. If not, 
      install it via your OS package manager. 
2. Folder Structure 
      Place the files and folders as follows: 
      project_folder/ 
      │ 
      ├── main.py # Your Python script 
      ├── model/ 
      │ └── mistral-7b-instruct-v0.1.Q4_0.gguf 
      └── vosk-model-en-us-0.22/ # Downloaded Vosk 
      STT model 
3. Download Required Models 
   Vosk Speech-to-Text Model 
      Download from: https://alphacephei.com/vosk/models 
      Use: vosk-model-en-us-0.22 
      Extract it and place the folder as vosk-model-en-us-0.22/ in the 
      project directory. 
   GPT4All Language Model 
      Download from: https://gpt4all.io/index.html 
      Use: mistral-7b-instruct-v0.1.Q4_0.gguf 
      Place it inside a folder named model/. 
4. Run the Project 
      Navigate to the project directory and execute the script: 
      python main.py 
5. Using the App 
      1. Launches a GUI Window 
      2. Select Role (e.g., Data Analyst, Software Developer) 
      3. Click “蘁蘂蘃 Start Interview” to begin 
      4. Type answers in the input box or 
      5. Use voice input: 
       - Click “藄藅藆 Start Recording” 
       - Speak your answer 
       - Click “脥� Stop Recording” when done 
      6. AI responds with follow-up questions 
      7. At the end, it gives an evaluation score and feedback 
6. Notes 
   i)  Make sure your microphone is functional.
   ii) If you're behind a firewall or antivirus, ensure microphone access is 
      allowed.
   iii) The app runs completely offline (no internet required after downloading 
      models). 
