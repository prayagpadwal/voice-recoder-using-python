# voice-recoder-using-python

To create a voice recorder using the Python programming language, you need to use the sounddevice library in Python. If you have never used this library before, you can easily install it by using the pip command mentioned below:

pip install sounddevice

The sounddevice library will help you to record your voice, but to save your voice in a specific file format, you need to use the SciPy library in Python, which can be installed by using the pip command:

pip install SciPy


In the above code, I have defined a Python function to record and save your recorded files. It takes two parameters:

The first parameter is seconds, where you will enter the number of seconds you want to record your voice.
The second parameter is the file, where you will input the name by which you want your recorded file to be saved. For example, “voice.wav”.
After running the above code, it will show you a message that the recording has started, and after the number of seconds that you have given as input, it will show you that the recording is complete. 

Once completed, it will automatically be saved to the same directory where your Python file is located.
 
