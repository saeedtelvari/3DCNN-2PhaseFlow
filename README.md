# 3DCNN-2PhaseFlow
Prediction of Two-phase Flow Properties for Digital Sandstones Using 3D Convolutional Neural Networks

# Instructions
- Inputs:
  - Image with a size of 400<sup>3</sup> Image 
  - Contact angle
  - IFT
- Image is normalized to (0,1)
- Contact angle and IFT are imported as is in SI units, e.g. [55, 0.03] (first parameter is contact angle and the second is interfacial tension)
- The input to the model will be an array with the following dimensions:
- [[num of samples, 400, 400, 400],  [contact angle, IFT]]  

I will upload a few sub-samples and demos in the near future
