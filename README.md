# Face Generation

In this project, I defined and trained a DCGAN on a dataset of celebrity images.The objective is to define and train a generator network to generate new images of faces that look as realistic as possible!

I have used [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train the adversarial networks.

Various tasks performed in this project are

- Preprocessed the data, cropping and resizing to square size
- Created a Dataloader with the desire batch size (=128)
- Scaled the image in the range of (-1,1) to match the output of generator network
- Defined the model architecture and initialized weights
- Defined loss functions
- Instantiated the model
- Defined model hyperparameters and 'train' function
- Defined optimizers
- Trained the model on GPU for epochs(=100)
- Visualized Training loss
- Visualized generated sample images at some iterations
- Summarized the learnings from this project






