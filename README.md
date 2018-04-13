# Rpi3_Voice
Raspberry pi 3 voice control
# Introduction:
  Offline Voice control of devices attached to Raspberry pi 3

# Required  Components:
  Raspberry pi 3 with updated  OS
  USB mic
  LED 
  150 ohm resistor
# Follow the steps >
## step1
  Setup the environmet of Rasbian OS

    sudo apt-get update

    sudo apt-get upgrade

It takes sometime if your build is old.
## step2
install `swig`, `sox`, `portaudio` and its Python binding `pyaudio` :

    sudo apt-get install swig3.0 python-pyaudio python3-pyaudio sox

    pip install pyaudio

Then install the `atlas` matrix computing library:

    sudo apt-get install libatlas-base-dev
    
Make sure that you can record audio with your microphone:

    rec t.wav
