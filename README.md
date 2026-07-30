The purpose of this project is to identify images handwritten Japanese hiragana from classical texts using stroke number, order, length and direction.

The loss and accuracy of two different models, a convolutional neural network (CNN) model, as well as a feed forward multi-layer perceptron (MLP) model, are compared to assess the model most well-suited to this task.

This project uses the Kuzujishi-MNIST (KMNIST-49) data from the following source:  
"KMNIST Dataset" (created by CODH), adapted from "Kuzushiji Dataset" (created by NIJL and others), doi:10.20676/00000341
>@online{clanuwat2018deep,  
  author       = {Tarin Clanuwat and Mikel Bober-Irizar and Asanobu Kitamoto and Alex Lamb and Kazuaki Yamamoto and David Ha},  
  title        = {Deep Learning for Classical Japanese Literature},  
  date         = {2018-12-03},  
  year         = {2018},  
  eprintclass  = {cs.CV},  
  eprinttype   = {arXiv},  
  eprint       = {cs.CV/1812.01718},  
}

Additionally, the dataset is downloaded using the GitHub code from the following repository:  
<https://github.com/rois-codh/kmnist/tree/master>
