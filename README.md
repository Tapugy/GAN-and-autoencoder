A class project for which I was tasked with creating 2 models an auto encoder for a dataset of celebrity images and a GAN to generate new images. 
While I was not happy with the results of the GAN due the quality being subpar I learned a lot from this project. I think to improve the quality of the model I have a few ideas 
1. Add more convolution layers with more filters and larger filters, when I wrote this project I did not know convultion layers could have multiple filters and
I didn't think too hard about the size of the filter a 2X2 is much too small to capture the celebs features
2. Use a dataset of PNG images rather than JPEG, especially for convultion. I noticed my peers on this project got better results removing convolution layers
   all togehter which shocked me since this went against the research the professor presented in class. I also noticed the images were jpeg rather than png which is mildly lossy.
   I theorized that this would have an effect on convolution which looks for specfic features and I went reading on this and ran into this paper (https://arxiv.org/pdf/2007.14314)
   which showed that lossy image compression had a statistically signifcant effect on model preformance on convolutional nerual networks.
3. My third theory is a bit boring but more epochs and/or more layers. I made the network small and trained it rather lightly for a GAN because my Mac has a weak gpu and
   I didnt have access to a gpu server so I think I could probably get better results with more training.
   
