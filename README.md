# image_compression

Here I implimented a Variational Autoencoders in Python with pytorch. A vae has 2 parts, encoder and decoder. Now the encoder part take an input and return a `mean vector`. This vector can be chamged into a `latent dimention` with the help of `std. dev. vec`. The decoder part the this as input and return a reconstructed input.    

I used a model for evaluation which is trained for 950 epoch. The performance is well. After 1000 epoch it did even better. You can check the large *[celebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)* dataset to perform the same technique, which can genetare the image of the celeb. After 600 epochs of training it did quite well on that data.     

THe datasets are in the fonts folder. 2 models are saved in the pretrained model folder. The notebook contains all the source code for this project. Some theory and resources are available on the notebook.    

### More resources
+ find more on variational autoencoder *[here](https://www.jeremyjordan.me/variational-autoencoders/)*
+ find variational inference *[here](https://ermongroup.github.io/cs228-notes/inference/variational/)*
+ find vae on youtube video *[here](https://www.youtube.com/watch?v=P78QYjWh5sM&feature=youtu.be)*
+ find official pytorch repo for vae *[here](https://github.com/pytorch/examples/tree/master/vae)*
