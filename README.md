## Converting-Text-to-Speech-in-Python

To implement this project, I have used the basic concepts of Python, Tkinter, gTTS, and playsound libraries.

Tkinter is a standard GUI Python library that is one of the fastest and easiest ways to build GUI applications using Tkinter.
gTTS (Google Text-to-Speech) is a Python library, which is a very easy library that converts the text into audio.
The playsound module is used to play audio files. With this module, we can play a sound file with a single line of code.

The objective of this project is to convert the text into voice with the click of a button. This project will be developed using Tkinter, gTTs, and playsound library. In this project, we add a message which we want to convert into voice and click on play button to play the voice of that text message.

Importing the modules
Create the display window
Define functions

Label() widget is used to display one or more than one line of text that users can’t able to modify.

root is the name which we refer to our window
text which we display on the label
font in which the text is written
pack organized widget in block
Msg is a string type variable
Entry() used to create an input text field
textvariable used to retrieve the current text to entry widget
place() organizes widgets by placing them in a specific position in the parent widget

Message variable will stores the value of entry_field
text is the sentences or text to be read.
lang takes the language to read the text. The default language is English.
slow use to reads text more slowly. The default is False.

As we want the default value of lang, so no need to give that to gTTS.

speech stores the converted voice from the text
speech.save(‘DataFlair.mp3’) will saves the converted file as DataFlair as mp3 file
playsound() used to play the sound

root.destroy() will quit the program by stopping the mainloop().
Reset function set Msg variable to empty strings.

root.mainloop() is a method that executes when we want to run our program
