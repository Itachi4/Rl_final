# Comparing RL Algorithms in Pong Environment

## Project Overview

This project focuses on comparing various Reinforcement Learning (RL) algorithms such as Proximal Policy Optimization (PPO), Actor-Critic methods, Deep Q-Network (DQN), and Double Deep Q-Network (DDQN) within a Pong game environment. The unique aspect of this project is the use of a Convolutional Neural Network (CNN) to process images, allowing the agent to learn solely from visual inputs.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## Introduction

This repository contains all the necessary code and documentation to run and analyze different RL algorithms. The goal is to determine which algorithm performs best in a controlled environment based purely on visual cues over 1,000 training epochs.

## Technologies Used

- **Python**: Version 3.x
- **TensorFlow/Keras**: For implementing the CNN
- **OpenAI Gym**: Pong environment
- **Other Libraries**: numpy, matplotlib (for data visualization)

## Setup

To run this project, install it locally using pip:

```bash
pip install -r requirements.txt


## Usage
To start the training process, run the following script:
python run_pong.py
