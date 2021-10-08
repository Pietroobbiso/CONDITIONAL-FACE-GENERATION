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
The best results were obtained by achieving a State of the Art FID score of 11.7! Some examples below:

* Female, young, attractive, brown_hair, bangs, heavy_make_up, no_beard

![alt text](https://user-images.githubusercontent.com/57104110/136577480-81236702-3963-4d59-bffb-c582cca756c7.png)


* Female, young, attractive, blonde_hair, smiling, eyeglasses, no_beard

![alt text](https://user-images.githubusercontent.com/57104110/136577861-b22c6e89-2ea0-48e8-bebb-0595345a8371.png)


* Male, attractive, brown_hair, straight_hair, smiling, eyeglasses, mustache

![alt text](https://user-images.githubusercontent.com/57104110/136577694-08a4f6bd-4eca-42fe-9c46-677f6d819b09.png)


* Male, pale_skin, bald, bushy_eyebrows, arched_eyebrows, no_beard

![alt text](https://user-images.githubusercontent.com/57104110/136578022-4243dd58-895f-4713-a6a1-c3353d4313b3.png)
