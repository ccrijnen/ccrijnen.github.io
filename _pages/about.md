---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm Cornelius, a PhD student in Psychology at Université de Montréal and [Mila](https://mila.quebec/en/directory/cornelius-crijnen), working with [Shahab Bakhtiari](https://mila.quebec/en/directory/shahab-bakhtiari).

I'm currently looking for a new PhD supervisor and planning to transfer to the computer science program. While my current research has provided valuable interdisciplinary experience at the intersection of AI and neuroscience, I’m aiming to return to core AI topics and join a lab more focused on deep learning. My interests include self-supervised learning, representation learning, multimodal learning, computer vision, generative models, machine learning theory, and reinforcement learning. If you're working in these areas and open to supervision opportunities, I’d be happy to connect.

At the moment, I'm working on [a project](#cross-species-analysis-of-visual-systems-understanding-visual-system-development-via-species-specific-movements) that investigates how neural networks can learn useful representations from video, with a focus on how species-specific movement patterns shape visual system development in the brain.

## Community & Teaching

Beyond research, I'm an active member of the UNIQUE Student Affairs Committee, where I help organize student conferences and social events like the UNIQUE Student Symposium (USS) and semesterly get-togethers featuring research presentations and networking opportunities for the NeuroAI community. I also love teaching and mentoring. Being a TA has been one of my favorite roles during my studies because it allows me to share knowledge, guide students, and help others develop their own understanding of deep learning. Whether it's through formal teaching or casual discussions, I find a lot of fulfillment in helping others grow.

## What Keeps Me Inspired

When I’m not doing research, you’ll likely find me doing outdoors or being active. I love running, rollerblading, bouldering, ice skating (during winter), biking, or simply being in nature. I'm currently training for my first marathon, which I once thought would be impossible. Rollerblading, especially urban and wizard skating, is one of my favorite hobbies. It's so much fun experimenting with gear and different skate setups too. I'm part of Montreal’s Rolling Tribes community, which has been a great way to stay active and meet people.

I also enjoy reading fantasy and sci-fi, listening to live music, and thinking about urban design. I care about cities being built around people instead of cars, which in my opinion drastically enhances daily life. Fun fact: I can solve a Rubik's Cube in under 30 seconds!

---

# Projects

## Cross-Species Analysis of Visual Systems: Understanding Visual System Development via Species-Specific Movements

This project investigates how distinct movement repertoires shape the visual systems of different species. By employing self-supervised learning (SSL) models trained on first-person video footage from rats and treeshrews, we compare the learned representations with neural data obtained from mice and macaques. Using Representational Similarity Analysis (RSA), we assess how these artificial neural network models align with biological visual systems, highlighting the impact of species-specific movement patterns on visual representation structures.

The project is nearing completion, and we are preparing a manuscript for submission now. Our findings indicate that visual experience, shaped by movement dynamics, is critical in determining the learned visual representations, both in biological and artificial systems.


## Visual Enhancement of Whole Brain Slide Images from Z-Scanning Microscopes with Deep Style Learning

![Training Pipeline](https://github.com/ccrijnen/Z-Stack-Enhancement/raw/main/reports/method/training.png)

In this master's thesis project, we developed the Z-Stack Enhancement (ZSE) pipeline, a deep learning framework implemented using Pytorch Lightning designed to enhance whole-brain microscopy images. This approach transfers the visual style from an in-focus reference image to out-of-focus images using a U-Net architecture combined with Adaptive Instance Normalization (AdaIN). The method effectively deblurs microscopic images, enhancing clarity and making it easier to study detailed brain structures.

### **Key contributions:**  
* Development of a novel deep style learning framework inspired by neural style transfer, specifically adapted for microscopy imaging.
* Introduction of two novel 3D loss functions optimized for image stacks, resulting in more realistic reconstructions of brain tissue. 
* Evaluation on two datasets, including super-high-resolution brain z-stacks from Research Center Jülich and microscopy images of Leishmania parasites, achieving state-of-the-art results with fewer parameters and improved generalization compared to existing methods.
* Public release of trained models and PyTorch implementation on a [GitHub Repository](https://github.com/ccrijnen/Z-Stack-Enhancement).  


## Playing Go with Recurrent Neural Networks

In this bachelor's thesis, we implemented neural network models using TensorFlow for playing Go via imitation learning, training on extensive datasets of expert human games. The project's goal was to evaluate different neural network architectures regarding their learning efficiency and effectiveness in mastering the game.

### **Key contributions:**  
* Implementation and comparison of two architectures: 
  * A RNN model consisting of a CNN backbone with an integrated ConvGRU layer for context summarization from past board states.
  * A CNN-only approach, inspired by AlphaGo Zero, utilizing additional input channels to encode past states without recurrence.
* Demonstration that the RNN-based model learned more efficiently compared to the CNN-only model, though both ultimately achieved comparable performance.
* Providing insights into the significance of temporal modeling for decision-making processes in reinforcement learning contexts. 
