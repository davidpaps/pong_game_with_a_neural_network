# Pong neural network:

I have been fascinated at the idea of machine learning ever since I started to code. I have recently been studying linear algebra, and its applications in the programming world. I came accross the idea of building a computer 'brain' that would lern and act a similar way to neurons in the brain - aptly named **neural networks** in the programming world!

This allowed me to discover the *TensorFlow* Python packages. These provide many pre set models to play with and explore these neural networks. This was my first project using Python, TensorFlow and Neural Networks as a whole! I used this project to play around with some basic ideas I have been having for a final project at Makers. 

---

As a ‘dry run’ I used the following [*tutorial*](https://www.youtube.com/watch?v=Hqf__FlRlzg&t=1309s) to help build the game, and then set about modifying the tensor flow code to learn from the pixel data it recieved from the pygame canvas.

---

## How to run the program:

Make sure you have a Python version between 3.4 - 3.7. Clone this repo and navigate to the directory in the command line, then type:

```
pip install --upgrade pip
```

This will check that pip is installed to the latest version, then type in the command line: 

```
pip install tensorflow
```

This will install the latest version of TensorFlow. Then type:

```
pip install opencv
```

This will Install OpenCV. Then type:

```
pip install pygame
```

This will install PyGame. By typing the following in the command line, we can run the game and watch the neural network train on the pong game:

```
python RL.py
```

The right paddle on the screen is linked to the neural network, and will therefore learn as time goes on (as it is trained more). The left paddle on the screen has random up/down inputs.

---
## AI in Action
<img src="images/screenshot.png">
