# Collaborative-ML-Fading-Channel-Model
This repo contains the code for year 3 undergraduate project titled "Machine Learning for Receiver Design", Student: Afzal Hamza, Supervisor: Dr. Mahdi Boloursaz Mashhadi, EEE Department, University of Surrey. The idea of this project is to have a federation of wireless users learn receiver data on their respective local neural networks and then collaborate to train a universal wireless receiver model.

# Dataset
The training dataset consists of 20'000 symbols and the test dataset consists of 1'000'000 16QAM symbols respectively. By nature of symbol composition, the neural network takes an input vector of size 2, as a result of the in-phase and quadrature components of the symbols. "y" values indicate the corresponding labels used to train the neural network. The default parameters are a federation of 5 users, each conducting 5 epochs of a batch-size of 20 per federation aggregation round, of which there are 5.

# Summary
![figure 3 1](https://user-images.githubusercontent.com/100214665/169526894-20b8d13e-0650-470f-880c-c2434ecf586b.jpg)
The above figure, figure 3.1. is pulled from the report which is accompanied by the code in this repo. It depicts reproduction of results from the literature using the code in this repo with a different fading-channel model; the Rician model, which is the personal contribution to the literature.   

# Questions?
If you have any further questions related to this repo, feel free to contact hamzaahmadafzal@gmail.com or raise an issue within this repo. I will do my best to reply as soon as possible.

# References
- M. B. Mashhadi, N. Shlezinger, Y. C. Eldar, and D. G ̈und ̈uz, “Fedrec: Federated learning of universal receivers over fading channels,” in 2021 IEEE Statistical Signal   Processing Workshop (SSP), 2021, pp. 576–580.
