# Music-Composer-AI
AI enabled Music Composer that helps user compose Novel Composition

Python Notebook uses deep learning algorithms wherein multiple layers of “neural networks” are programmed to music information between various input and output notes. 

We have taught this deep neural network to understand the art of music composition by reading through a large database of classical music written (not limited to) by the most famous composers (Bach, Beethoven, Mozart, etc). AI Composer is capable of capturing concepts of music theory just by doing this acquisition of existing musical works. After having listened to a large amount of music and learned its own models of music theory, model composes its very own music. This Model was initially trained on 50 Piano .MIDI files -  and some of the newly created composition samples are in the repo. CPU based training took over 30 mins. With increase in model complexity (More Layers + Input files = 100 .MIDI files), model took around 4 hours of trainng time. For larger data-set & complex architecture, GPU based training is recommended (Update Tf code for accomodating GPU). 

Encourage you to take A MUSICAL TURING TEST on samples or have it when you create something on your own. This small project is result of a weekend of effort, so a lot of scope & room is available for exploration(Hyper-tuning, Seq2Seq based Architecture et al.) & expansion (Multiple-Instruments, Different input formats et al.).

To use the python notebook, create a folder /train & put .MIDI files into it. Notebook is configured to encode .MIDI files into relevant data-format required for the AI Model to generate ouput. Output generated by the AI based composer model is then decoded & .MIDI format file output is created locally. Since the training data-set had Piano .Midi Files, so the pre-trained model in the repo is trained for piano. In case you have .MIDI files for drum, you can have an AI model for drum.

Futher you can modify and have hybrid model that combines Piano & Drum Notes to generate compositions containing multiple instruments (Expansion).

Dependencies
============

* Numpy (http://www.numpy.org/)
* Tensorflow (https://github.com/tensorflow/tensorflow)
* Python Mido
* Python Matplotlib
* Python Sklearn

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies
