# CONDITIONAL-FACE-GENERATION

## Description
In this project we investigate several techniques of generative models. Among them, we focus our attention on the ones considered by us the best in terms of results furnished. The goal here is to provide the best generation of images having specific attributes chosen directly by the user. 
We work with CelebA dataset containing more than 200k images and 40 attributes annotations per image. The quality of the generated images is measured using the Fréchet Inception Distance (FID).

![alt text](https://user-images.githubusercontent.com/57104110/136570871-795253b7-f514-45d8-a471-0568c9cc618b.png)

## Model Architecture
For all experiments we used the same DCGAN (Deep Convolutional Neural Networks) architecture, structured in the following way:

DISCRIMINATOR              | GENERATOR
:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/57104110/136574739-17668993-2321-4c3b-9e6d-3efacf92deaf.png) | ![](https://user-images.githubusercontent.com/57104110/136574554-73fcf4d8-0c80-4b44-a76c-b33b910dc221.png)

## Results
The best results were obtained by achieving a State of the Art FID score of 11.7! Some examples:

*Female, young, attractive, brown_hair, bangs, heavy_make_up, no_beard
![alt text](https://user-images.githubusercontent.com/57104110/136577318-26a95ede-567f-4dcc-a36d-bfc6b3b4522f.png)



