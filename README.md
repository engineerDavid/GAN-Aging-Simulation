#Aging Simulation using CycleGAN

#How to Run program
1.)Open AgeCycleTrain notebook file in Colab
2.)Download data organized data https://drive.google.com/file/d/1jBl-5eqxHx6vY-_j5GCW7mCHQtajlVnU/view?usp=sharing and upload to google to your google drive in a folder called "Scripts"
3.)Run and allow Colab to access drive folder "Scripts" to access training data
4.)Wait a few hours
5.)Results! (Sometimes when Colab has too much traffic available ram for free users is reduced and you may get an out of ram error. To restart, select "Restart and Run all" in the Runtime menu at the top of Colab)

#Abstract 
	
A generative adversarial network (GAN), is a type of machine learning that works by making two neural networks compete against each other. Their competition is a zero-sum game, and through multiple runs each neural network gets better at their respective job. The two jobs are that of the generative network and the discriminative network. The generative network attempts to trick the discriminative network into making errors by generating data that increases the error rate. The discriminative network attempts to decrease the error rate, and as a result these two networks help each other improve leading to the discriminative network becoming better at doing its task.
In this project a GAN was trained for aging simulation. Aging simulation was selected because nearly every year there are hundreds of thousands of missing children reported in America and around the world. Children not found over long spans of time need have their age simulated. The current method of doing so is an age progression photo software called PhotoSketch. PhotoSketch requires a professional artist to age the photo. This creates a barrier to entry to use this sort of technology because law enforcement would need to have an artist on hand and the funding to maintain up-to-date aged photos for each missing child. It also requires that the artist be specifically trained in how to age people. In the United States the local law enforcement may have access to the resources and artists to do this occasional updates to missing persons images, however in developing countries that may not necessarily be the case.

References


[1] Grigory Antipov, Moez Baccouche, and Jean-Luc Dugelay. 2017. Face aging with conditional generative adversarial networks. In 2017 IEEE International Conference on Image Processing (ICIP), 2089–2093. DOI:https://doi.org/10.1109/ICIP.2017.8296650

[2] Xinhua Liu, Chengjuan Xie, Hailan Kuang, and Xiaolin Ma. 2018. Face Aging Simulation with Deep Convolutional Generative Adversarial Networks. In 2018 10th International Conference on Measuring Technology and Mechatronics Automation (ICMTMA), 220–224. DOI:https://doi.org/10.1109/ICMTMA.2018.00060

[3] Ashish Shrivastava, Tomas Pfister, Oncel Tuzel, Josh Susskind, Wenda Wang, and Russ Webb. 2017. Learning from Simulated and Unsupervised Images through Adversarial Training. arXiv:1612.07828 [cs] (July 2017). Retrieved October 30, 2020 from http://arxiv.org/abs/1612.07828

[4] Lipeng Wan, Jun Wan, Yi Jin, Zichang Tan, and Stan Z. Li. 2018. Fine-Grained Multi-Attribute Adversarial Learning for Face Generation of Age, Gender and Ethnicity. In 2018 International Conference on Biometrics (ICB), 98–103. DOI:https://doi.org/10.1109/ICB2018.2018.00025

[5]Chun Yang and Zhihan Lv. 2020. Gender based face aging with cycle-consistent adversarial networks. Image and Vision Computing 100, (August 2020), 103945. DOI:https://doi.org/10.1016/j.imavis.2020.103945

[6] Zhifei Zhang, Yang Song, and Hairong Qi. 2017. Age Progression/Regression by Conditional Adversarial Autoencoder. arXiv:1702.08423 [cs] (March 2017). Retrieved October 30, 2020 from http://arxiv.org/abs/1702.08423

[7] Jun-Yan Zhu, Taesung Park, Phillip Isola, and Alexei A. Efros. 2020. Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks. arXiv:1703.10593 [cs] (August 2020). Retrieved October 30, 2020 from http://arxiv.org/abs/1703.10593
 


