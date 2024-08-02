Library Imports: Imported essential libraries including speech_recognition, pyttsx3, pywhatkit, datetime, wikipedia, and pyjokes to handle voice recognition, text-to-speech, YouTube playback, time retrieval, Wikipedia searches, and joke generation.

Voice Recognition Setup: Initialized the speech recognizer and text-to-speech engine, setting the voice property to ensure clear and understandable speech output.

Speech-to-Text Function: Developed a function take_command() to capture voice input from the microphone, recognize speech using Google's speech recognition, and convert it into text.

Command Processing: Implemented the run_alexa() function to interpret and execute various commands such as playing songs on YouTube, telling the current time, fetching Wikipedia summaries, and telling jokes.

Continuous Listening: Created a loop to continuously listen for voice commands, ensuring the virtual assistant is always ready to respond to user requests.
