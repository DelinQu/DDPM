# DDPM
In this repo, I implement the diffusion probabilistic model (DDPM) proposed by Ho et al~\cite{ho2020denoising} for synthesizing high-resolution images. 
My approach employs a Markov chain Monte Carlo sampling technique to approximate the posterior distribution of the model parameters, 
allowing us to generate high-quality images that accurately capture the underlying data distribution. 
I provide a detailed description of the principle behind the DDPM and present experimental results on Konachan~\footnote{aistudio: \url{https://aistudio.baidu.com/aistudio/datasetdetail/110820}}, CelebA-HQ~\cite{CelebAMask-HQ} and CIFAR10~\cite{CIFAR10} dataset. In addition, I compare the characteristics and limitations of DDPM with other state-of-the-art generative models, such as generative adversarial networks (GANs)~\cite{goodfellow2020generative}, variational autoencoders (VAEs)~\cite{Kingma2013AutoEncodingVB}, and flow-based models~\cite{JimenezRezende2015VariationalIW}. Furthermore, I survey current applications of the DDPM in the field of computer vision. Overall, My results demonstrate the effectiveness of the DDPM for image synthesis tasks and highlight its potential for various applications in the field.
![image](https://user-images.githubusercontent.com/60593268/208427647-da7a5390-9314-470f-87db-5591a532c863.png)



# Experiments
- Generated samples on CelebA-HQ [22] dataset
![image](https://user-images.githubusercontent.com/60593268/208427528-4981c0af-206d-410e-b8cd-93d9db0689ca.png)

- Generated samples on n Konacha dataset
![image](https://user-images.githubusercontent.com/60593268/208427774-2622a286-ef3d-4522-9d58-ac8121eedb3e.png)

- Generated samples on n CIFAR10 [21] dataset
![CIFA10](https://user-images.githubusercontent.com/60593268/208427865-0be6565b-f649-46c2-b9a6-5d5265230fd9.png)


