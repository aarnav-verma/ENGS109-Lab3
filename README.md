# ENGS109 Lab 3

Coding assignment 3 for ENGS109, covering parts 3A, 3B, and 3C.


part 3a, sparse encoder, we sampled thosuands of 8x8 patches from natural iamges and implemented a sparse encoder that learned to represent these patches usinga  few active neurons. functions for sampling, computing, the cost, and gradients of autoencoder, checked implementation via numerical gradient checking. tranied the network, then visualized the weights to see if we had discovered the edges in teh data or nto

part 3b. 
- this was a simplified gpt lke transformer, tokenized  a shakespeare corpus, built a model with posirtional embeddings, mutli-head self attention and feed forward layers, and trained it to predict the next character. the notebook wrote most of the code tbh, but ut ewas interesting to see.
- the model was meant to introudce core processess between LLMs]

- 
- the parameter choices were mainly focusing on keeping the model large enough to b e practical, but still to see meaningful patterns.
- as training progressed, loss decreasesd

part 3c
- focused on implementing basic denoising diffusion probabilistic model to generate MNIST digits.
- implemented a noise scheduler, sinusoidal embeddings, a small u net and training sampling functions
- all images are in the notebook itself

- lab has helped me better understand how transformers work in practice, its now less abstract
