Analyzing images with codes can be difficult. Therefore, it's necessary for you to make your code understand the context of an image. In doing so, the first step will be identifying the dominant colors.
----

[Hint: Refer the following url for image processing documentation: http://omz-software.com/pythonista/docs/ios/PIL.html]

Objective: To identify the dominant color in the image.
----

Action to Perform:

- Open and display the image “dog.jpeg.”
- Use K-means clustering for image segmentation, which will include the following steps:
- Find out the dimensions of the image and convert it to a two-dimensional array.
- Use K-means clustering with k set to 3 and cluster the image.
[Hint: Refer to the K-means module of scikit learn]
- Predict the cluster label of every pixel in the image and plot it back as an image.
- Find out the three dominant colors in the image.
[Hint: The cluster centers should correspond to three dominant colors]
