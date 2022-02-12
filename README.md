# Music Spectogram Classification
Spectogram Image classification using deep learning in MATLAB

Spectograms are visual representations of sound signals at different frequencies in the form of waves. They are used in various fields for processing radiation, linguistics, music, and so on. In a spectogram, time is plotted on the Y-axis and frequencies on the X-axis to represent changes in frequencies over time, from left-to right, high to low. This article describes a deep learning experiment performed using MATLAB in which about 2000 spectogram images of 14 musical instruments - bells, cello, clarinet, crotales, double bass, flute, piano, saxophone, trombone, trumpet, vibraphone, viola, violin and xylophone are used. The dataset is obtained from the [University of Iowa Electronic Music Studios](https://theremin.music.uiowa.edu/index.html) . The images stored in separate folders for each instrument are split into three augmented datastores where 80% is for training, 10% for validation and balance for test. In the first experiment, a convolutional neural network created from scratch and in the second experiment transfer learning is used.

This project has two parts -

1. Music spectogram classification [using CNN ](https://github.com/khushboo-gehi/MusicSpectogramClassification/blob/main/Part%202/scratch.pdf)
 
2. Music spectogram classification [using Transfer Learning](https://github.com/khushboo-gehi/MusicSpectogramClassification/blob/main/Soln/transfer_learning.pdf)
