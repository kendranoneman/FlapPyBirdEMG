FlapPyBirdEMG
===============

A clone of a flappy bird [clone](https://github.com/sourabhv/FlapPyBird) that can be played with any microphone input. This project is compatible with Backyard Brain's [SpikerBox](https://backyardbrains.com/products/spikerboxBundle).  

How-to (as tested on MacOS)
---------------------------
Additional pip packages such as `pyaudio`,`PyGame`,etc... may have to be installed too.

1. Clone the repository or fork/clone your own:

   ```bash
   $ git clone https://github.com/kendranoneman/FlapPyBirdEMG.git 
   $ git clone git@github.com:kendranoneman/FlapPyBirdEMG.git
   ```

   or download as zip and extract.

1. In the root directory run

   ```bash
   $ pipenv install
   $ pipenv run python flappy.py
   ```

1. Use <kbd>&uarr;</kbd> or <kbd>Space</kbd> key to play and <kbd>Esc</kbd> to close the game.

(For x64 windows, get exe [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pygame))

Notable forks
-------------

- [FlappyBird Fury Mode](https://github.com/Cc618/FlapPyBird)
- [FlappyBird Model Predictive Control](https://github.com/philzook58/FlapPyBird-MPC)
- [FlappyBird OpenFrameworks Port](https://github.com/TheLogicMaster/ofFlappyBird)
- [FlappyBird On Quantum Computing](https://github.com/WingCode/QuFlapPyBird)

Made something awesome from FlapPyBird? Add it to the list :)


ScreenShot
----------

![Flappy Bird](screenshot1.png)

[pygame]: http://www.pygame.org
[pipenv]: https://pipenv.readthedocs.io/en/latest/
