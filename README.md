## Inspiration
Our algorithm was inspired from companies and startups such as Qure AI who have the goals of integrating healthcare and computer science in order to achieve levels of precision and arithmetic accuracy that no human can hope to achieve. We hope to start using the power of computer science and artificial intelligence to have our own impact on the field of medicine.

## What it does
Our program revolves around using Tensorflow and Keras to identify and classify any MRI (magnetic resonance imaging) of the brain to identify signs of the Alzheimer's disease and calculate how far they are. We used a multi-class image recognition algorithm to classify any new MRI scan we input into specified classes.

## How we built it
We built it using Tensorflow and Keras to use convolutional neural networks and a trained model in order to train with a dataset of 6400 brain scans and tested it with a subset of the images in order to obtain its accuracy at around 95%. We built a prediction segment where the model that we trained can predict the degree of the Alzheimer's in the patient and move that MRI scan into the respective subdirectory in the file system ie. move a moderately demented image into a subdirectory containing all MRI scans of moderately demented individuals.

## Challenges we ran into
We ran into multiple challenges on the way where the code would simply not run due to the size of the dataset and the limited power of the machines we were using. Secondly, using a local-runtime, our Google Colab session would continuously. Our Datalore environment in its free form wasn't tuned to support such training. Hence, we could only rely on one laptop to train the model, and even with that it takes 20 minutes.

## Accomplishments that we're proud of
We managed to build a full-fledged deep learning algorithm which responds to our inputs when we submit any scans obtained from random sources. We built an image classification program which can classify images real-time which is something e didn't think we would be able to build before.

## What's next for BrainSplitter
This algorithm can be expanded to many different types of datasets and use cases such as brain tumours, kidney stones identifying any cardiac functions working incorrectly etc.
