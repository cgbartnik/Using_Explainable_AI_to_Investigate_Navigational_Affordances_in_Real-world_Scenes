# Using Explainable AI to Investigate Navigational Affordances in Real-world Scenes

This repository contains the python code used for the CRS21 Poster it contains code to load the used Stimuli and behavioral data collected from an online experiment and different XAI feature visualizations. The anotated paths are quantitativly analyzed and the different feature spaces are compared using reprsentational similarity analysis (RSA). 

![Poster](/poster_CRS.png)

## Abstract

**Using Explainable AI to Investigate Navigational Affordances in Real-world Scenes**
*Clemens G. Bartnik and  Iris I.A. Groen*
*Video & Image Sense Lab, Informatics Institute, University of Amsterdam, The Netherlands*

Moving through the world requires extracting navigational affordances from our immediate environment. How do we compute navigational affordances from visual inputs and which visual features are important? Recent work shows that navigational affordances of indoor scenes are captured by deep convolutional neural networks (CNNs) trained for scene recognition (Bonner & Epstein, 2018). Here, we investigated the ability of CNNs to capture affordances in a broader set of environments using different explainable AI feature visualizations (GradCam, LRP, LIME) and different task objectives/network models (depth perception, scene segmentation). We curated a diverse set of 231 naturalistic real-world indoor, outdoor man-made and outdoor natural scenes and collected human annotations depicting which path trajectory participants (N=152) would take through the scene. Visual inspection shows that path drawings are quite consistent among participants and thus diagnostic features for potential paths are present. Using representational similarity analysis, we find that across all environments, no single CNN feature representation correlates best with human path annotations. For indoor environments, highest correlations were found with GradCam visual explanations of important regions for the class prediction, and layout-related information captured by CNN-generated depth maps. In contrast, for outdoor natural and outdoor man-made environments LRP activations, highlighting the impact of input pixels on the class prediction, correlated best with human annotations. These results show that no single CNN feature representation adequately captures navigational affordances, and that future models need to incorporate multiple relevant features that humans use to perceive a possible path through natural scenes.


