In my code, the PCA class can be used very easily, there are all functions including plotting one by one, 
only the dataset matrix and the number n are entered as parameters.

There is also a function that creates a dataset matrix directly when you discard the image list. 
The dataset matrix can be created that way and can be used again for the PCA algorithm.

in the same way, I have a function that directly returns histogram features and PCA components 
by giving the photo matrix and n number, but the desired feature can be obtained by optionally 
changing the bin parameter in the histogram feature.

Finally, I have a function that calculates the distance between different images based on the euclidean 
distance and returns the closest 10 images, and I have a function that calculates and prints the mean 
average precision for each category connected to these 10 images, and these can only be used by giving 
the outputs of the previous functions as parameters.

