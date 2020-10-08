# SignLanguage_MNIST
Open as a Hacktoberfest repository. 

## The MNIST Dataset
- The original MNIST image dataset of handwritten digits is a popular benchmark for image-based machine learning methods but researchers have renewed efforts to update it and develop drop-in replacements that are more challenging for computer vision and original for real-world applications. 
- The dataset format is patterned to match closely with the classic MNIST. Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions). The training data (27,455 cases) and test data (7172 cases) are approximately half the size of the standard MNIST but otherwise similar with a header row of label, pixel1,pixel2….pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255. 

### Why begin with the MNIST dataset?
- The MNIST dataset is a well-known dataset for image classification. 
- Tensorflow and Keras also provide MNIST dataset directly through their APIs.
- A relatively easy dataset for beginners to try out

### Task
- To identify and classify the images into 10 classes [0-9] respectively
