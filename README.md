# text-to-speech-of-AI-module
from gtts import gTTS
import os
mytext = 'hi AL !'
language = 'en'
myobj = gTTS(text=mytext, lang=language, slow=False)
myobj.save("welcome.mp3")
os.system("start welcome.mp3")
