# 🧠 AI Flappy Bird using NEAT

This is a mini-project where an AI learns to play the Flappy Bird game using the NEAT algorithm (NeuroEvolution of Augmenting Topologies). It uses Python, Pygame, and the neat-python library to train birds to play the game automatically.

---

## 📌 Project Overview

- 🎮 Recreated the Flappy Bird game using `pygame`
- 🧬 Trained a population of birds using the NEAT algorithm
- 🧠 Neural networks evolve over generations to improve performance
- ✅ Includes a pre-trained model (`best.pickle`) to watch the AI play
- 📈 Visualizes the neural network using `visualize.py`

---

## 🗂️ Project Structure

NEAT-Flappy-Bird/

│

├── flappy_bird.py 👉 Main Python file (game + NEAT training loop)

├── visualize.py 👉 Neural network visualization tool

├── config-feedforward.txt 👉 Configuration for NEAT algorithm

├── best.pickle 👉 Saved trained model

├── imgs/ 👉 Game assets (bird, pipe, background)

├── *.ipynb 👉 Jupyter notebooks for testing

├── requirements.txt 👉 List of required Python libraries

└── README.md 👉 Project documentation

---

## 🛠️ Installation

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/ai-flappy-bird-neat.git
   cd ai-flappy-bird-neat
2.Install dependencies:

   pip install -r requirements.txt
3.▶️ How to Run
   To train and watch the AI play:
     python flappy_bird.py
The AI will begin training using NEAT. You can adjust NEAT settings in config-feedforward.txt.
You can also load and run the pretrained model (best.pickle) for instant results.

## 🧠 Technologies Used

 1.Python 3

 2.Pygame – for game interface

 3.neat-python – for neuroevolution algorithm

 4.matplotlib & graphviz – for visualizations

## 📷 Screenshots 

![image](https://github.com/user-attachments/assets/7bd628e7-28da-48fa-bddb-5f2a798e8652)


## 📚 What I Learned
How neuroevolution (NEAT) works

How to integrate AI into a game environment

How to visualize and analyze neural networks

Reinforcement-style training for AI agents

## 🙌 Credits
neat-python

Game assets inspired by the original Flappy Bird

Concept inspired by Code Bullet & Tech with Tim

# 👤Author
Yogeswaran Apparaj

Based on a tutorial by Tech With Tim, with personalized enhancements and cleanup.

