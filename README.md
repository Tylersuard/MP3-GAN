# MP3-GAN
Generating Audio Music using Generative Adversarial Networks

## Procedure:

1. I downloaded the FMA Dataset: https://github.com/mdeff/fma/
2. I converted the clips into images using PhotoSounder
3. I cropped the images to 10-second clips
4. I resized all images to be 512x512 pixels
5. I trained StyleGAN, a generative adversarial network, to create new images similar to the audio images I created
6. StyleGAN created similar images, which I then converted back into sound using PhotoSounder

Included: the easy Colab training and generating notebooks for StyleGAN
