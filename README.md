# ChatterSox
Python class to control 1 servo motor to respond to audio volume levels to mimic jaw movement for robots. Based heavily off of ChatterPi but scaled down to the absolute minimum

Designed to be as basic as possible, this single class takes in an Adafruit Servo and a Digital IO output pin, it will mute and unmute a speaker to allow audio to play, play an audio wav file, and give the option to move the jaw with respect to volume, or just play the audio

.talk(path) uses the path to an audio file and plays it while moving the jaw.

.play(path) uses the path to an audio file and plays it
