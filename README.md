# 3DCNN-2PhaseFlow
Prediction of Two-phase Flow Properties for Digital Sandstones Using 3D Convolutional Neural Networks

# Instructions
The input for this model requires the following:

1. An image with a size of 400<sup>3</sup> pixels.
2. Contact angle value.
3. Interfacial tension (IFT) value in SI units.
- Image should be normalized with pixel values in the range of (0,1).
The contact angle and IFT are to be imported as-is in SI units, where the first parameter is contact angle and the second parameter is interfacial tension, e.g., [55, 0.03].

In summary, the input to the model should be an array with the following dimensions:
<p align="center"> [[num of data rows, 400, 400, 400],  [num of data rows, contact angle, IFT ]]  </p>

- We recommend using numpy format for images and physical parameters.
- We will also be uploading a few sub-samples and demos in the near future for your reference.
