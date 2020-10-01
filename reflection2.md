# Data Science Reflection #2: Tone Transfer

Google Research and Magenta teamed up to create a new machine learning model called Tone Transfer. The model takes sounds inputted by a user and transforms them into pieces played by musical instruments. You can input the sound of your cat meowing, and have the model return a flute, saxophone, trumpet, or violin solo. Tone Transfer is able to transform these sounds through the use of a new machine learning process called Differentiable Digital Signal Processing (DDSP). 

Regular Digital Signal Processing (DSP) evaluates different audio elements, such as filters, reverberations, and oscillators. This is used by many audio tools, including synthesizers, to manipulate and change sounds. But, because of the simple controls of synthesizers, the sounds created end up sounding quite artificial. Therefore, DDSP uses deep learning and a neural network to precisely control the simple DSP elements and create incredibly realistic sounds.

Tone Transfer uses this DDSP library and machine learning to learn the exact tone of an instrument from a small amount of data. With the DDSP technology, Tone Transfer was trained on only a 10 minute recording of an instrument. As it was trained, the model learned to extract complex relationships between pitch, tone, volume, and reverberations. After training, the Tone Transfer models can form high quality audio renders of the instrument from other sounds. It can even recreate other performance sounds, such as the key clicks on a saxophone or the breathing sounds from a trumpetist or flutist. The model can also render new sounds that can’t even be made by the base instrument. Furthermore, the Tone Transfer models are flexible and even allow the user to adjust the pitch and volume of their sound after it has been transformed into the output instrument.

At the moment, the main limitation of the software is that it only works with monophonic sounds, or when only one note is playing at a time. Thus, it cannot convert chords or harmonies into the base instruments. Despite this limitation, the model is still quite impressive, and very entertaining to experiment with.

You can try the software out for yourself by clicking [here](https://sites.research.google/tonetransfer)

#### Sources:
