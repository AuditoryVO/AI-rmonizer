# AI-rmonizer
Stellar spectra-driven unsupervised music composition system.

CONTENTS
- Jupyter notebook 1: 1-DeepVAE_4dim.ipynb
- Jupyter notebook 2: 2-Latent2Chords_4dim.ipynb
- Jupyter notebook 3: 3-MAESTRO2numpy.ipynb
- Jupyter notebook 4: 4-AI-rmonizer_Demo.ipynb
- LICENSE
- README
- requirements.txt

INSTALLATION

- Download all the content into the same folder

Generating stellar score:
- Download the stellar spectra from: http://svocats.cab.inta-csic.es/miles/index.php?action=credits
- Open the Jupyter notebook 1-DeepVAE_4dim.ipynb and introduce your paths to the downloaded spectra
- Run the Jupyter notebook with all the dependencies installed

Preprocessing:
- Run the Jupyter notebook 2-Latent2Chords_4dim.ipynb
- Download the MAESTRO dataset from: https://magenta.tensorflow.org/datasets/maestro
- Open the Jupyter notebook 3: 3-MAESTRO2numpy.ipynb and introduce your paths to the downloaded MIDI files
- Run the Jupyter notebook

Generating the final spectra-driven score:
- Download the pre-trained weights from Zenodo : https://zenodo.org/record/8342535
- Download the MIDI file: http://www.jsbach.net/midi/midi_solo_cello.html
- Open the Jupyter notebook 4, AI-rmonizer_Demo.ipynb, and introduce your paths to the downloaded files
- Run Jupyter notebook with all the dependencies installed
- Enjoy the piece!
