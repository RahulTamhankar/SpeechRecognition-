# SpeechRecognition-
This is a real time speech recognition project to search videos on youtube

What is speech recognition?
The ability of a machine or programme to recognise words spoken aloud and translate them into legible text is known as voice recognition, often known as speech-to-text. Basic voice recognition software can only pick out words and phrases that are uttered clearly and has a small repertoire. More advanced software can handle diverse languages, accents, and natural speech. Speech Recognition is used in Apple Siri, Google Assistant etc.
There are many python packages for Speech Regognition in Python-
-SpeechRegognition
-google-cloud-speech etc

Python Packages I have used- SpeechRegognition
SpeechRegognition Class used- Recognizer()
This class has about 7 methods by which it can recognize speech from an audio source with the help of various APIs.
There methods are-
recognize-googel-cloud()
recognize_google()
recognize _ibm()
recognize_bing()

There methods can help us hit various APIs which use neural network to convert speech to text.

Important Necessary Libraries which I have used are-
import speech_recognition as spr- Will be used to perform speech to text translation
import webbrowser as wb- WIll be used to launch a web browser
import pafy- Will be used to retrive imformation from YouTube
import urllib.request- Used to fetch URLs
from bs4 import BeautifulSoup- Used to perform web scrapping for a HTML page

![image](https://user-images.githubusercontent.com/87760177/212671914-0ea55b29-6386-4e11-82ff-594f85c7f601.png)

About this Project-

This Real Time Speech Recognition to Search Youtube Video is a small project that allows users to speak commands into their computer's microphone so that the Speech Recognition API can comprehend them. Once the voice command has been recorded. The voice command captured will then trigger a web based query in web browser  to automatically open the YouTube.com search page and look for a specific video using the user's spoken keyword.

Test-

![image](https://user-images.githubusercontent.com/87760177/212538561-ef6dde8c-75f1-4995-9aa3-581ba4a90b5d.png)

Output-

![image](https://user-images.githubusercontent.com/87760177/212538523-da2da1c5-41d0-44ed-aaf7-353223e350ac.png)

Future Scope I will be working on-
i will be trying to play the top video of YouTube page in VLC media player
#import vlc- 
#import time
