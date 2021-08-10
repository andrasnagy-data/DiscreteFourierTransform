### Discrete Fourier Transform (DFT) with Fast-Fourer Transform algorithm

For this project, I recorded  myself singing 1 octav (each notes). 
Then I used Audacity to cut (create same length) and create a "combined.wav".
Later, I used the so-called pydub module, to transform the stereo to mono audio signal.
Lastly, I applied the DFT to the combined.wav file, to decompose it into "individual" frequencies.
![image](/plots/DFT_individuals_lows.png)
Above is the DFT of the "individual" audios that "make up" the combined.wav.
![image](/plots/DFT_combined_lows.png)
Above is the DFT of the combined.wav.

Lastly, I created a spectogram ("visual representation of the spectrum of frequencies of a signal as it varies 
with time" - wikipedia) of the combined.wav. The spectogram of combined.wav:
![image](/plots/combined_spectogram.png)



**Conclusion:** The algorithm managed to produce an (almost) identical representation of combined.wav, in terms of the decomposed frequencies.

