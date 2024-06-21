FlapPyBirdEMG
===============

A clone of a flappy bird [clone](https://github.com/sourabhv/FlapPyBird) that can be played with any microphone input. This project is compatible with Backyard Brain's [SpikerBox](https://backyardbrains.com/products/spikerboxBundle).  

Setup (as tested on MacOS)
---------------------------
Additional pip packages such as `pyaudio`,`PyGame`,etc... may have to be installed too.

1. Clone the repository or fork/clone your own:

   If you have SSH keys configured:
   ```bash
   $ git clone git@github.com:kendranoneman/FlapPyBirdEMG.git
   ```
   OR 
   ```bash
   $ git clone https://github.com/kendranoneman/FlapPyBirdEMG.git 
    ```
   or download as zip and extract.

2. In the root directory, run

   Create the environment from the environment.yml file:
   ```bash
   $ conda env create -f flappybird.yml
   ```
   Activate the new environment:
    ```bash
   $ conda activate flappybird
   ```
   Verify the environment was installed correctly:
    ```bash
   $ conda env list
   ```
    <img width="534" alt="Screenshot 2024-06-21 at 12 21 42 PM" src="https://github.com/kendranoneman/FlapPyBirdEMG/assets/37158560/59b21f59-6d30-47ba-a8c7-7d72d189c4c9">


1. Use <kbd>&uarr;</kbd> or <kbd>Space</kbd> key to play and <kbd>Esc</kbd> to close the game.

(For x64 windows, get exe [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pygame))

Running FlappyBird
---------------------------
1. In the root directory (with the conda environment activated), run
   ```bash
   $ python flappyemg.py
   ```
   This *won't* run the game, but it'll show you the options of **Input Devices** you have to pick from.
   When the SpikerBox isn't plugged into the computer, I see these options listed as input devices:
   * Device number (0): MacBook Pro Microphone
   * Device number (1): MacBook Pro Speakers
   * Device number (2): Kendra’s iPhone Microphone
   * Device number (3): Microsoft Teams Audio
  
   But, when the SpikerBox is plugged in another option will pop up (I can't remember right now which one it is lol).
   But you'll use that device number (X) to run the game using that input. 
    ```bash
   $ python flappyemg.py -input X
   ```

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
