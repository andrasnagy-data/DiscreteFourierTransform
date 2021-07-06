### Discrete Fourier Transform (DFT) with Fast-Fourer Transform algorithm

For this project, I recorded  myself singing 1 octav. 
Then I used Audacity to cut and create a "combined.wav".
Later, I used the so-called pydub module, to transform the stereo to mono audio signal.
Lastly, I applied the DFT to the cimbined.wav file, to decompose it into "individual" frequencies.
[image](plots/DFT_individuals_lows.png)
This is the DFT of the "individual" audios that "make up" the combined.wav.
[image](plots/DFT_combined_lows.png)
And this is the DFT of the combined.wav.

Lastly, I created a spectogram of the combined.wav, with the intention of later using this technique,
to classify sounds by using a pre-trained computer vision model (transfer learning).
The spectogram of combined.wav:
[image](plots/combined_spectogram.png)