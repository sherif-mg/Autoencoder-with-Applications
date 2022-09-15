# Autoencoder-with-Applications

Autoencoders  are an unsupervised learning technique in which we leverage neural networks for the task of  representation learning. 

Specifically, we'll design a neural network  architecture such that we impose a bottleneck in the network  which  forces a compressed knowledge representation  of the original input.  

Autoencoders  compress the input into a lower-dimensional code and then reconstruct the output from this representation. The code is a compact “summary” or “compression” of the input, also called the latent-space representation.

![This is an image](https://github.com/sherif-mg/Autoencoder-with-Applications/blob/main/Autoencoder.png)

If the input features were each independent of one another, this compression and subsequent reconstruction would be a very difficult task. 
However, if some sort of structure exists in the data (ie. correlations between input features), this structure can be learned and consequently leveraged when forcing the input through the network's bottleneck.

**Applications of Autoencoder:**

1- Dimensionality Reduction<br/>
Dimensionality Reduction is the process of reducing the number of dimensions in the data either by excluding less useful features (Feature Selection) or transform the data into lower dimensions (Feature Extraction).

2-Anomaly Detection<br/> 
Anomaly detection is the process of identifying unexpected items or events in data sets, which differ from the norm. And anomaly detection is often applied

3-Denoising 

4-Image colorization
