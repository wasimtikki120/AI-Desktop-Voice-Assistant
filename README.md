# AI-Desktop-Voice-Assistant

Welcome to the AI Desktop Voice Assistant, a Python-based voice-activated assistant that performs various tasks based on voice commands.

Overview
This assistant is designed to execute a range of functionalities using speech recognition. It can search for information on Wikipedia, open specific websites, tell the current time, and even send emails. It utilizes various Python libraries for speech recognition, text-to-speech conversion, web browsing, and data retrieval.

Features
Wikipedia Search: Retrieve information from Wikipedia based on user queries.
Web Browsing: Open specified websites like YouTube, Google, and Stack Overflow.
Time Information: Provide the current time on request.
Email Functionality: Send emails by providing the recipient and content.
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/AIDesktopVoiceAssistant.git
Install Required Libraries:

bash
Copy code
pip install pyttsx3 speech_recognition wikipedia
Set up Email Configuration:

Edit the sendEmail() function in the main.py file, providing your email credentials to enable email-sending functionality.

Usage
Run the Application:

bash
Copy code
python main.py
Command the Assistant:

Once the assistant greets you, it will prompt "Listening..."—start speaking commands.
Examples of commands include "Search Wikipedia for...", "Open YouTube", "Tell me the time", or "Send an email".
Customization
Modify the assistant's voice, greeting messages, or add new functionalities by editing functions in the main.py file.
Contribution
Feel free to contribute by forking the repository and creating a pull request. Contributions could include enhancing functionalities, fixing bugs, or adding new features.

License
This project is licensed under the MIT License. You are free to use, modify, and distribute the code.

Acknowledgements
This project uses the pyttsx3, speech_recognition, and wikipedia libraries.
