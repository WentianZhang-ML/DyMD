# Dynamically Masked Discriminator for GANs
This repository provides the official PyTorch implementation for the following paper (_The code will be released soon._): 

**Dynamically Masked Discriminator for GANs** ([Paper]())

 > **Abstract:** *Training Generative Adversarial Networks (GANs) remains a challenging problem. The discriminator trains the generator by learning the distribution of real/generated data. However, the distribution of generated data changes throughout the training process, which is difficult for the discriminator to learn. In this paper, we propose a novel method for GANs from the viewpoint of online continual learning. We observe that the discriminator model, trained on historically generated data, often slows down its adaptation to the changes in the new arrival generated data, which accordingly decreases the quality of generated results. By treating the generated data in training as a stream, we propose to detect whether the discriminator slows down the learning of new knowledge in generated data. Therefore, we can explicitly enforce the discriminator to learn new knowledge fast. Particularly, we propose a new discriminator, which automatically detects its retardation and then dynamically masks its features, such that the discriminator can adaptively learn the temporally-vary distribution of generated data. Experimental results show our method outperforms the state-of-the-art approaches.*
