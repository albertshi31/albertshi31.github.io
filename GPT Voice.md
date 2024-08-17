## Voice Recognition with ChatGPT

<img width="781" alt="Screenshot 2024-08-16 at 7 42 49 PM" src="https://github.com/user-attachments/assets/537ecdf8-0d70-4a14-9afb-7371cc03725e">

[GPT Voice Recognition Demo](https://youtu.be/zrXF_Pf65AI)

[GPT 2.0 Code](https://github.com/albertshi31/GPT-Project/blob/main/gpt2_generate.py)  
[UPDATED: GPT 3.5 Code](https://github.com/albertshi31/GPT-Project/blob/main/gpt3.5project.py)

In this project, I developed a voice-activated AI chatbot that integrates BERT for intent classification and GPT-3.5 for generating conversational responses. The system can recognize spoken input, classify the intent of the speech, generate a relevant response, and convert the response to speech.

Speech Recognition:
- Utilizes the speech_recognition library to capture and recognize spoken input from a microphone.
- Listens for speech, processes it, and converts it to text using Google Speech Recognition.

Intent Classification with BERT:
- Sets up a BERT model (bert-base-uncased) using the transformers library for classifying intents from the spoken input.
- Classifies intents into categories such as Query, Command, Information, Request, Feedback, and Greeting.

Response Generation with GPT-3.5:
- Uses OpenAI's GPT-3.5 to generate conversational responses based on the classified intent and the user's prompt.
- Implements OpenAI API for generating responses dynamically.

Text-to-Speech Conversion:
- Converts the generated text response to speech using the gTTS (Google Text-to-Speech) library.
- Saves the speech output as an MP3 file and plays it back using system-specific commands for Windows, macOS, and Linux.

Easter Egg Feature:
- Includes a fun Easter egg that opens a Rick Roll video on YouTube if the spoken input contains the keyword "banana."


