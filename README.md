# Diffusion_model
Diffusion models play an important role in Generative AI for example generating a video or an image out of a context or a prompt. 

## Components
The diffusion model consists of 3 main components which includes:
- Noise Scheduler
- Neural Network
- Timestep Encoding

## Main flow
The noise is added to the image according to avery timestep and then the noise is converted back to the image using the timestep and eliminating the noisy image at timestep t - noise to achieve the image to be generated at timestep t-1.

## The noise schedular formula
![image](https://github.com/Aliza-Adnan/Diffusion_model/assets/113924925/40ee6bff-c40a-45b4-ac8e-2375c5c20bc0)

## The neural network formula and architecture
The architecture used is of UNET and following is the formula used:
![image](https://github.com/Aliza-Adnan/Diffusion_model/assets/113924925/b8c4748c-37c6-4d65-9a4c-d5abc3836acf)
![image](https://github.com/Aliza-Adnan/Diffusion_model/assets/113924925/51f42fec-205d-4ae0-9a8a-891828029ae2)

## Timestep encoding formula
![image](https://github.com/Aliza-Adnan/Diffusion_model/assets/113924925/7cefe231-99a6-4723-a2de-0d3aaaa3cb01)
![image](https://github.com/Aliza-Adnan/Diffusion_model/assets/113924925/c2fe2f21-0734-4961-94e5-c3da0ea4d80c)

## Credits:
https://www.youtube.com/watch?v=a4Yfz2FxXiY
