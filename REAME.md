# P3-DL: Autoencoders in STL-10

Pablo Diaz
Dani Prieto

## TODO mas o menos ordenado

- [ ] Change the baseline AE to use a dense latent space, reduce it in size as well.
- [ ] Train the baseline AE and the three AEs with different convolutional sizes.
- [ ] Add denoising AE to the best performing AE and train it. Test with noise {0.05, 0.15}.
- [ ] Add a variatoional AE to the best performing AE and train it. Test with different values of the KL divergence weight (beta) {0.5, 1.0}.

- [ ] In a new notebook, compare the performance of the different encoders trained by using the same classification head on top of the latent space. Train them with the same configuration and compare the results.

- [ ] If possible retrain the best model in CESGA with the whole unllabeled set and see if it improves the results.
