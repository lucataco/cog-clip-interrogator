# AiBaby-Pics Cog model

This is an implementation of a custom model for generating baby pics, as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog build -t clip

Then, you can run predictions:

    cog predict -i image=@turtle.jpg
