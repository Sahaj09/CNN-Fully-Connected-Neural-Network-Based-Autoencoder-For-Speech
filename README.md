# CNN-Fully-Connected-Neural-Network-Based-Autoencoder-For-Speech

The dataset used for this project is TIMIT
(https://catalog.ldc.upenn.edu/LDC93S1)

For CNN_Based_Autoencoder-
  
  Just follow the CNN_Based_Autoencoder.ipynb file

  Make sure you change the directory
  
For Fully-Connected-Neural-Network-Based-Autoencoder-

  Run the pre_process_for_RIFF.ipynb first to convert files into RIFF format,
  
  Run the Fully-Connected-Neural-Network-Based-Autoencoder.ipynb,
  
  Make sure you change the directory
 
 

In both the implemented methods in this repository, the phase is ignored for reconstruction as the motive of this repo was to come up with simple models for speech compression. The output time-domain signal is reconstructed using griffin-lim algorithm for spectograms (CNNs) and irfft for rfft values (Fully-Connected).
