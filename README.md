# GAN_new_renaissance_art

This is the GANs model that we have created using input images from WikiArts.org (10,5k images in renaissance and baroque style). This is Keras based GAN.

This repository contains sample code which includes resizing of the pictures to 128x128, discriminator, generator and includes running function of Generative adversarial network.
You can view “GAN_new_renaissance_art” directly on github, or clone the repository, install the dependencies listed and play with code locally. As well it contains a little part of the input and results of the model.

## How does it work?
 This GAN combines two networks: Discriminator ,which defines the real(database images) and fake images, and Generator, which generates noise creating new pictures. After generating new pictures by Generator network the output is send to discriminator to give feedback. 
 
 In our model database is recreated into array in order to increase the speed of the GAN model. What is more it is printing the ongoing epoches which gives feedback on the process. Both networks are learning constantly with each epoch. The outcome is being saved after each 100 epoch.
 
 In order to launch this code you need Pillow, OS and Numpy liberies.

### here are few results of our work (epoch 9400)
![image](https://user-images.githubusercontent.com/59648881/81001529-281cff80-8e48-11ea-842a-0b7cda5ef335.png)





It is recomended to train it on GPU in order to train it faster.
We would love to see your results under #new_gan_art or you can share your outputs directly messaging us.


  https://github.com/RoRaKa29

  https://github.com/eweeels

  https://github.com/bunczii
  
  https://github.com/Zelferr



