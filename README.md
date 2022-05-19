# Vehicle CAN Cybersecurity with Machine Learning

Today’s vehicles are complex distributed cyber-phsyical systems that are increasingly being connected to various external systems. Unfortunately, this increased connectivity makes the vehicles vulnerable to security attacks that can be catastrophic. We have developed a novel Intrusion Detection System (IDS) called INDRA that utilizes a Gated Recurrent Unit (GRU) based recurrent autoencoder to detect anomalies in Controller Area Network (CAN) bus-based automotive cyber-phsyical systems. 

![INDRA overview](https://github.com/EPIC-CSU/vehicle-cybersecurity/blob/main/indra-overview.jpg)

The code in this repository is a barebones implementation of the INDRA anomaly detector for CAN networks in emerging automotive platforms. The code is written in Tensorflow v2 and Pytorch, and tested on Google Colab. 

If you use this code for your research, please cite the following paper: 

V. K. Kukkala, S. V. Thiruloga, and S. Pasricha, “INDRA: Intrusion Detection using Recurrent Autoencoders in Automotive Embedded Systems”, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, (TCAD), 39(11), Nov 2020. 
