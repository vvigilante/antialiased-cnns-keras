# Making Convolutional Networks Shift-Invariant Again (antialiased-cnns, keras port)

This repository contains a keras porting of the work "Making Convolutional Networks Shift-Invariant Again" by Richard Zhang, published in ICML 2019, original code in torch available at <a href=//github.com/adobe/antialiased-cnns>github.com/adobe/antialiased-cnns</a>. Any work using this code must cite that work. This code is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

The porting of the BlurPool layer comes with an vgg-face pretrained implementation of SENet from <a href="//github.com/rcmalli/keras-vggface">github.com/rcmalli/keras-vggface</a> where the strided convolutional layers and the pooling layers use BlurPool. 
If you wish to add more example architectures or more pre-trained weights, you are welcome!

Run antialiasing.py for testing the BlurPool layer alone.
