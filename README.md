## Library for Processing WAV Audio Files

### Introduction

### Available functionalities
Options   Information

-list<br />Meta-information export for a list of .wav audio files

-mono<br />Converts the audio file from stereo (existence of 2 channels) to monophonic (existence of only one channel). 

-mix<br />Mixing of two tracks

-chop<br />Slices an audio file from one given second to another.

-reverse    Inverts the data of an audio file.

-similarity   Checks the similarity per byte of the given audio files. The similarity test is based on two algorithms: (a) the Euclidean matching technique and (b) Longest Common Subsequence (LCSS) matching.

–encodeText   Hides a text file inside a wav audio file.

–decodeText   Decrypt / Recover secret text from a WAV audio file

### Usage
Compile: 
`make clean`

`make`

Execute:
`./wavengine <-option> sound1.wav [ sound2.wav sound3.wav ...]`
