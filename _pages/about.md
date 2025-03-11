---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm Cornelius, a PhD student at Université de Montréal in Psychology, working with [Shahab Bakhtiari](https://mila.quebec/en/directory/shahab-bakhtiari). I'm passionate about deep learning and AI, with a focus on self-supervised learning (SSL), representation learning, computer vision, generative models, and reinforcement learning.

Currently, I’m particularly interested in **video representation learning with SSL**, exploring how neural networks can learn structured and meaningful representations from raw video data. I’m fascinated by how AI models can capture temporal dynamics and how these representations can be applied to various downstream tasks.

## Building community

Beyond research, I care deeply about fostering an inclusive and engaging academic community. I'm an active member of the UNIQUE Student Affairs Committee, where I help organize student events, research presentations, and networking opportunities for the NeuroAI community. I also love teaching and mentoring. Being a TA has been one of my favorite roles during my studies because it allows me to share knowledge, guide students, and help others develop their own understanding of AI. Whether it's through formal teaching or casual discussions, I find a lot of fulfillment in helping others grow.

## What Keeps Me Inspired

When I’m not working on AI, you’ll likely find me outdoors: running, rollerblading, ice skating, biking, or just enjoying nature. I’m an avid reader, particularly of fantasy and sci-fi, and love getting lost in new worlds through books. I also have a passion for live music, urban design, and well-integrated public transport. Seeing cities built for people rather than cars is particularly of interest to me, and I enjoy thinking about how thoughtful urban planning can improve daily life. Fun fact: I can solve a Rubik's Cube in under 30 seconds!

---

# Projects

## Cross-Species Analysis of Visual Systems: Understanding Visual System Development via Species-Specific Movements

This project investigates how distinct movement repertoires shape the visual system of different species. Using self-supervised learning (SSL) trained on first-person video footage from rats and treeshrews, I compare the learned representations with neural data from mice and macaques. Through Representational Similarity Analysis (RSA), I analyze how these models align with biological visual systems, revealing how species-specific movement patterns influence visual representations. The results indicate that visual experience alone, shaped by movement dynamics, plays a crucial role in determining the structure of learned visual representations, even in artificial neural networks.  


## Visual Enhancement of Whole Brain Slide Images from Z-Scanning Microscopes with Deep Style Learning

For my master’s thesis, I developed the Z-Stack Enhancement (ZSE) pipeline, a deep learning framework implemented in *Pytorch Lightning* that enhances whole-brain microscopy images by transferring the visual style of an in-focus reference image to out-of-focus images. Using a U-Net with Adaptive Instance Normalization (AdaIN), this method deblurs microscopic images, improving clarity and aiding researchers in analyzing fine cellular structures.  

![Training Pipeline](https://github.com/ccrijnen/Z-Stack-Enhancement/raw/main/reports/method/training.png)

### **Key contributions:**  
* Developed a novel deep style learning framework inspired by neural style transfer, adapted for microscopy images.  
* Introduced two 3D loss functions for optimizing image stacks, enabling more realistic reconstructions of brain tissue.  
* Evaluated on two datasets, including super-high-resolution brain z-stacks from Research Center Jülich and Leishmania parasite images, showing state-of-the-art performance with fewer parameters and better generalization than existing methods.  
* Publicly released the trained models and PyTorch implementation [GitHub Repository](https://github.com/ccrijnen/Z-Stack-Enhancement).  


## Playing Go with Recurrent Neural Networks

In my bachelor’s thesis, I implemented neural networks in *TensorFlow* for playing Go via imitation learning, training on hundreds of thousands of expert human games. The goal was to explore different architectures and their efficiency in learning the game.  

### **Key contributions:**  
* Implemented two competing architectures:  
  * Recurrent neural network (RNN) approach A CNN backbone combined with a ConvGRU layer to summarize context from past board states.  
  * CNN-only approach (inspired by AlphaGo Zero): Encoded past states using additional input channels rather than a recurrent structure.  
* Found that the RNN-based model learned more efficiently than the CNN-only approach, while ultimately reaching similar performance.  
* Provided insights into the effectiveness of temporal modeling for decision-making in reinforcement learning tasks.  
