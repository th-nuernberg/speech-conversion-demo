# Demo Page for "Generative Models for Improved Naturalness, Intelligibility, and Voicing of Whispered Speech"

### Authors

- [Dominik Wagner](mailto:dominik.wagner@th-nuernberg.de) (TH Nürnberg)
- Sebastian P. Bayerl (TH Nürnberg)
- Hector A. Cordourier Maruri (Intel Labs)
- Tobias Bocklet (TH Nürnberg, Intel Labs)

### Paper 

Accepted at the 2022 IEEE Spoken Language Technology Workshop (SLT 2022)

### Code
The source code is available on [GitHub](https://github.com/dwgnr/speech-conversion).


### Abstract

This work adapts two recent architectures of generative models and evaluates their effectiveness 
for the conversion of whispered speech to normal speech. 
We incorporate the normal target speech into the training 
criterion of vector-quantized variational autoencoders (VQ-VAEs) and MelGANs, 
thereby conditioning the systems to recover voiced speech from whispered inputs. 
Objective and subjective quality measures indicate that both VQ-VAEs and MelGANs 
can be modified to perform the conversion task. We find that the proposed approaches significantly 
improve the Mel cepstral distortion (MCD) metric by at least 25% relative to a DiscoGAN baseline. 
Subjective listening tests suggest that the MelGAN-based system significantly improves naturalness, 
intelligibility, and voicing compared to the whispered input speech. 
A novel evaluation measure based on differences between latent speech representations 
also indicates that our MelGAN-based approach yields improvements relative to the baseline.     
