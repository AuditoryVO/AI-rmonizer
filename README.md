# AI-rmonizer
Stellar spectra-driven unsupervised music composition system.
![AIRMONIES-GitHub](https://github.com/AuditoryVO/AI-rmonizer/assets/144262864/84691096-eb8a-4334-9c5c-3acafd478fce)

CONTENTS
- Jupyter notebook 1-DeepVAE_4dim.ipynb
- Jupyter notebook 2-Latent2Chords_4dim.ipynb
- Jupyter notebook 3-MAESTRO2numpy.ipynb
- Jupyter notebook 4-AI-rmonizer_Demo.ipynb
- LICENSE
- README
- requirements.txt

CABBAGE/CSOUND INSTALLATION

1- Download and install CSound 6.15 from: https://github.com/csound/csound/releases/tag/6.15.0

2- Download Cabbage from: https://cabbageaudio.com/download/ 

3- Install only Cabbage from the downloaded Cabbage package.

   Warning: The latest version of Cabbage allows to optionally install the latest version of CSound. This default option should be unchecked not to overwrite CSound 6.15.
   Latests versions of CSound require additional plugins to work with the image CSound opcodes, so they should not be used.


AI-RMONIZER INSTALLATION

1 - Download all the content of this repository into the same folder

2 - Install all the dependencies included in the requirements.txt file

Generating stellar score:
1 - Download the stellar spectra from: http://svocats.cab.inta-csic.es/miles/index.php?action=credits
2 - Open the Jupyter notebook 1-DeepVAE_4dim.ipynb, and introduce your paths to the downloaded spectra
3 - Run all cells in the Jupyter notebook 

Preprocessing:
1 - Run the Jupyter notebook 2-Latent2Chords_4dim.ipynb
2 - Download the MAESTRO dataset from: https://magenta.tensorflow.org/datasets/maestro
3 - Open the Jupyter notebook 3-MAESTRO2numpy.ipynb, and introduce your paths to the downloaded MIDI files
4 - Run all cells in the Jupyter notebook

Generating the final spectra-driven score:
1 - Download the pre-trained weights from Zenodo : https://zenodo.org/record/8342535
2 - Download the MIDI file: http://www.jsbach.net/midi/midi_solo_cello.html
3 - Open the Jupyter notebook 4-AI-rmonizer_Demo.ipynb, and introduce your paths to the downloaded files
4- Run all cells in the Jupyter notebook

Enjoy the piece!
