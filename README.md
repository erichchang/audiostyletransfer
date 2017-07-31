# Audio Style Transfer - COSMOS Cluster 9 2017

<p align="center"> <i>Audio Style Transfer</i> aims to create unique audio samples by combining a base audio file and style audio file. We attempted to apply a computer vision technique known as "style transfer" to an image. </p>


<p align="center"> <b>Eric Chang, Mark Endo, John Guibas</b> </p>

<p align="center"> <img src="https://cosmos-ucop.ucdavis.edu/Contents/i/cosmos-logo.png" width="200"> </p>

# Style Tranfer

*Style tranfer* requires two different files: a content and a style. The style is extracted from the file and applied to the content. In this case, the content is the notes of the content file, while the style is how the style file is played, such as rhythm or instruments. The objective of the style transfer is to get the program to play the content audio file in the style extracted from the style audio file.

# Spectrogram

*A spectrogram* is a visual representation, or graph, of the frequencies of sound over a period of time. In this case, there are separate spectrograms for the two different audio files, content and style. There is also a final spectrogram showing the style transfer audio file. The lines in the spectrogram show the pitches, or notes. The background color on the spectrogram represents the amound of noise behind the sound.

<p align="center"> <img src="http://i.imgur.com/vP90hGB.png" width="600"> </p>

# Tonnetz

*Tonnetz* is a diagram that shows tones in space without using frequency numbers. It was first introduced by Euler to show tonal space and tone relationships in terms of thirds or fifths. In this experiment, tonnetz are used to change the loss function of sound.

<p align="center"> <img src="https://upload.wikimedia.org/wikipedia/commons/6/67/TonnetzTorus.gif" width="600"> </p>
