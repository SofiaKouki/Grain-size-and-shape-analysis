This model is designed to perform automated segmentation and classification of sediment features.
It focuses on identifying specific particle properties and categorizing them into distinct classes.
The pipeline starts by using a U-Net-based convolutional neural network to segment images, separating grains from the surrounding matrix.
Once the grains are segmented, the model extracts a range of geometric and shape-related properties for each particle.  
These properties include roundness, elongation, and rugosity, as well as measurements like perimeter, Feret’s diameter, and overall particle size.
The classification stage employs several machine learning algorithms, including support vector machines (SVM), logistic regression, and Naive Bayes. 
The model is trained on a balanced dataset that ensures equitable representation across different particle categories (for roundness, elongation, and rugosity). 
