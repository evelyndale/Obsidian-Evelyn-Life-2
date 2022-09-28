### Table of Contents
1. [[#DECIBELS|DECIBELS]]
1. [[#METERING|METERING]]
	1. [[#METERING#Peak and RMS|Peak and RMS]]
	1. [[#METERING#LUFS / LKFS|LUFS / LKFS]]
1. [[#Classic Processor Types|Classic Processor Types]]
	1. [[#Classic Processor Types#EQUALIZERS|EQUALIZERS]]
		1. [[#EQUALIZERS#Pultec Style (Push/Pull)|Pultec Style (Push/Pull)]]
		1. [[#EQUALIZERS#Dynamic|Dynamic]]
	1. [[#Classic Processor Types#COMPRESSORS|COMPRESSORS]]

# Decibels
 Decibels are logarithmic, and are only relative. A frame of reference is needed, such as dbFS. The formula is dB = 10 x log( power2 / power1 )

Physical Unit | Abbreviation | 0 dB Reference Point
---------- | --------------- | ---------------------
Sound Pressure | dB SPL | 0dB = 0.00002 pascals (human hearing threshold)
Analog Audio Meter | dB VU (Volume Units) | 0 dB = +4 dBu (1.228volts rms)
Digital Audio Meter | dB FS (Full Scale) | 0 dB = Maximum Volume in a Fixed-point System


# Metering
### Peak and RMS
RMS usually has ~300ms window. "Crest Factor" describes peak-to-average comparison. 
PSR = Peak - Loudness (Peak to Short-Term Loudness Ratio)
### LUFS / LKFS
Essentially interchangeable, weighted measurement that takes into account that humans hear different frequencies at different perceived loudnesses. The three types are Momentary, Short-Term (average of about 3 seconds), and Integrated (the entire span of the piece of audio being measured, e.g. a whole song or whole tv show)


# Classic Processor Types
### Equalizers
**Pultec Style (Push/Pull)**
Used for low end. The classic "boost and attenuate" trick boosts the low bass range while dipping slightly in the mid bass. 
