---
date: 2025-05-08 12:00:00
layout: post
title: "Image Recognition"
subtitle: "Emotion Recognition"
description: >- 
  A game I made using x86 assembly language.
category: Artificial Intelligence
image: /assets/img/emotionRecog.png
optimized_image: /assets/img/emotionRecog.png
tags:
  - C#
  - Python
  - Unity
  - Visual Studio
  - Visual Studio Code
  - TensorFlow/Keras
  - Flask
author: izabela
---

A multiplayer puzzle game in Unity where players communicate using **facial expressions** instead of voice or text. The core idea was to explore new ways of interaction and reduce toxic behaviour in games.

The game uses a **real-time** emotion recognition system powered by deep learning. A CNN model **(DenseNet, ~72% accuracy)** was trained on the **FER-2013** dataset to detect emotions like happiness, anger, and surprise from webcam input. The model runs in Python and sends live predictions to Unity via a Flask API, where player avatars update dynamically to reflect their emotions

Gameplay is built around this mechanic—players solve puzzles by interpreting each other’s expressions. If prolonged anger is detected, the game triggers a calming mini-game based on breathing techniques, encouraging players to reset before continuing.

> As this was created during my time in university, the university owns this project. Due to this, I cannot share the project code or files. See below for screenshots/videos from the game.

## Video Demo

<iframe width="100%" height="400"
  src="https://www.youtube.com/embed/MteQQawkRyM"
  frameborder="0"
  allowfullscreen>
</iframe>