# AI_meeting_minutes
Create AI meeting minutes 
Flow run AI meeting minutes 

1. Import necessary modules: The script starts by importing necessary modules. openai is used to interact with the OpenAI API, docx is used to create Word documents, speech_recognition is used for speech recognition, and subprocess is used to spawn new processes, connect to their input/output/error pipes, and obtain their return codes.

from openai import OpenAI
from docx import Document
import speech_recognition as sr
import subprocess

2. Initialize OpenAI client: The script then initializes the OpenAI client with your API key. This client will be used to make requests to the OpenAI API.

client = OpenAI( # OpenAI API key

3. Define functions: The script likely defines several functions to perform tasks such as extracting the abstract summary, key points, and action items from the transcription, performing sentiment analysis, generating meeting minutes, and saving the minutes as a Word document.

4. Main script execution: After defining the functions, the script likely uses them to process a transcription and generate meeting minutes. This might involve calling the functions with the transcription as an argument, and then saving the resulting minutes as a Word document.

minutes = meeting_minutes(transcription)
save_as_docx(minutes, filename)

Go to this website to create another API Key: https://platform.openai.com/api-keys
