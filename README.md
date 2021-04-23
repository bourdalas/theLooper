# theLooper

## Introduction

This is The Looper design and implementation repository. TheLooper is a standalone audio-processing device using:

1. A custom sturdy aluminum and wooden case.
2. custom midi input hardware modules  
3. One arduino-mega:
	1. Map hardware midi input 
4. One rasberry-pi with pisound card (https://blokas.io/pisound/):
	1. Use arduino midi input
	2. Audio processing engine (JUCE C++)
	3. Other functonalies 



## Repo should contain:

1. Case: 
	1. Design files.
	2. Implementation details.

2. Hardware:  
	1. midi input modules schematics 
	2. pcb design cad files  
	3. implementation details.

3. Arduino: 
	1. for controlling the hardware midi input

4. Rasberry: 
	1. for controlling the looper audio engine and rasberry functionalities


## Repo now contains:

1. Case:
	1. Possible implementation steps

2. Hardware:  
-

3. Arduino: 
	1. MIDI_controller: This is a library for creating a MIDI controller using an Arduino board. *Already-Tested* arduino library that will make the arduino code seem pretty pretty easy to do.

4. Rasberry: 
	1. HelloLooper: A ready github repo, where a simple looper JUCE app is implemented. This repo could be used as the core of the looper audio engine 

