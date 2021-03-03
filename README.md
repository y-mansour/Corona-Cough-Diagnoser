# Corona-Cough-Diagnoser

This repository contains the code for reproducing the results from the paper: https://drive.google.com/file/d/1mjSCuPF9tYyZCspLgFvhrD5qxL6ADH8o/view?usp=sharing. It is recommended to install Pytorch, Tensorflow, Librosa, Pydub and common python libraries such as numpy and matpotlib to run the notebooks with no problems. The notebook "coughs" was run on cuda (Linux).

The goal here is to compare the results of two different approaches for diagnosing corona from cough audio samples. The dataset is already included in the repository and was downloaded from: https://github.com/virufy/virufy_data. In the first cell in the notebook you can choose the device depending on if you will run on cpu or gpu. 
