# [CSUN-AI-Jam-2019](https://youtu.be/zgxMGaI28I4)
We used a deep learning convolutional neural network to train a model to recognize A.S.L. hand gestures in real-time.

Our original idea was to have a mobile application that you can download on your phone to translate A.S.L. hand gestures in real-time. So far, we have only trained our model to recognize A.S.L. letters. 

If we were to expand on this idea, we would need more images for each hand gesture to have a more accurate model. Next, we would expand the number of gestures the model can recognize instead of solely focusing on ASL letters. Finally, we would need to port the AI over to a mobile environment for users to download.

### Dependencies
- Python3 (3.6.7)
- Cython (You will have to build the Cython module)
- Tensorflow
- Numpy
- Opencv 3

### How to install?
- [Linux/macOS](https://gist.github.com/simonw/0f93bec220be9cf8250533b603bf6dba)

- [Windows](https://github.com/thtrieu/darkflow)

### How to use?
- After you have installed the dependencies, run the ```real-time.py``` script to launch the project.

### Video
- [link](https://youtu.be/zgxMGaI28I4)

#### Notes:
##### This was written using Python 3.6.7.
##### You need to have a camera installed in order for the script to properly execute.
