# DeepDream with a few changes

This version of the DeepDream code has a few changes to the original code:
* varying stepsize and iteration count over the octaves
* optional class suppression
* optional maximum und blur filtering of activation layers
* a given image size for the first octave instead of a scale factor
* optional desaturation
* a utility function to load images from local paths and remote urls


If you are new to this you should start with the original version:

This repository contains IPython Notebook with sample code, complementing 
Google Research [blog post](http://googleresearch.blogspot.ch/2015/06/inceptionism-going-deeper-into-neural.html) about Neural Network art.
See [original gallery](https://photos.google.com/share/AF1QipPX0SCl7OzWilt9LnuQliattX4OUCj_8EP65_cTVnBmS1jnYgsGQAieQUc1VQWdgQ?key=aVBxWjhwSzg2RjJWLWRuVFBBZEN1d205bUdEMnhB) for more examples.

You can view "dream.ipynb" directly on github, or clone the repository, 
install dependencies listed in the notebook and play with code locally.

It'll be interesting to see what imagery people are able to generate using the described technique. If you post images to Google+, Facebook, or Twitter, be sure to tag them with [#deepdream](https://twitter.com/hashtag/deepdream) so other researchers can check them out too.

* [Alexander Mordvintsev](mailto:moralex@google.com)
* [Michael Tyka](https://www.twitter.com/mtyka)
* [Christopher Olah](mailto:colah@google.com)
