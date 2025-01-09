---
title: "SEFR - Self Engineered Functional Requirments for Image Classification Systems"
collection: teaching
type: "Course Project"
permalink: /research/sefr
venue: "Department of Computer Science"
date: 2024-08-01
location: "Toronto, Ontario"
---
<!-- 
In this work, we consider image classifications models in larger software systems - and thus construct functional requirments for said system based on categories of inputs on which our image classifcation performs well vs poorly. This is done through an auxiliary image captioning system which allows interpretable representation of inputs over which our image classificaiton system may fail.  -->

Computer vision models (CVM) are increasingly being incorporated into software systems to enable key functionality. Upholding the reliability of software systems enabled by computer vision components is an important field of study. While a lot of contemporary work focuses on how these computer vision components can be augmented for increases robustness, the augmentation of software systems to facilitate machine learning components is still understudied. From existing literature, we feel that the demand for a (i) Machine-Verifiable, (ii) Interpretable and (iii) Model Aware guardrail has not been met, with contemporary techniques only solving parts of the puzzle at a given time.

In this paper, we propose a method -  ValCap to add machine verifiable and human interpretable input validation in software system, to improve their overall reliability. ValCap using image captioning models to create input validation critera based on the presence or absense of key words. This input validation method is both machine verifiable and human-interpretable - and is aimed to increase the reliability of CVMs, whilst reducing their scope. In our experimentation we demonstrate that (i) Lexical information from captions is correlated with features extracted by CVM, (ii) Lexical information from captions from some input can inform the performance of an image classification model on that input, (iii) Qualifying and Disqualifying inputs based on their associated captions can improve the overall performance of image classification models.

I worked under the supervision of Professor Marsha Chechik.