# CRNN (Chemical Reaction Neural Network)

CRNN is an interpretable neural network architecture for automonously inference chemical pathways in various chemical systems. It is designed by on the following two fundamental physics laws: the Law of Mass Action and Arrhenius Law. It is also possible to incoorperate other physics laws to adapt CRNN to a specific domain.

<p align="center">
<img src="./assets/CRNN_TOC.png" width="500">
</p>

You can find the common questions regarding CRNN in the [FAQs](https://github.com/DENG-MIT/CRNN/wiki/FAQs).

# Structure of this repo

This repo provides the case studies presented in the orginal CRNN paper as well as ongoing prelimanry results on other systems.

Inside each folder, such as case1/2/3, you will find at least two Julia codes. One for traing and the other one for weight pruning. Those two files are basically identical, except that the weight pruning includes a function to pruning the CRNN weights to further encourage sparsity.

# Cite
Ji, Weiqi, and Sili Deng. "Autonomous Discovery of Unknown Reaction Pathways from Data by Chemical Reaction Neural Network." arXiv preprint arXiv:2002.09062 (2020). [pdf](https://arxiv.org/abs/2002.09062)
