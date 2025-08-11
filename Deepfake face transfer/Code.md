## Face Motion Transfer Demo

This project demonstrates the implementation of **First Order Motion Model for Image Animation**, originally developed by Aliaksandr Siarohin et al.

The implemented notebook transfers the facial expressions and movements from a driving video to a source image, effectively animating the image based on the video’s motion.

The code is adapted from the original [Google Colab Demo](https://colab.research.google.com/github/AliaksandrSiarohin/first-order-model/blob/master/demo.ipynb) provided in the official repository:  
[https://github.com/AliaksandrSiarohin/first-order-model](https://github.com/AliaksandrSiarohin/first-order-model)

### How it works
- **Input**: A static source image + a driving video.
- **Output**: A new video where the source image is animated to follow the movements and expressions from the driving video.
- **Core technology**: Deep learning-based motion transfer using keypoint detection and dense motion prediction.

This implementation is purely for research and educational purposes.
