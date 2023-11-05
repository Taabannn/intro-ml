# HW3
### Q6
* Goal: Implementing a 4-layer MLP network to classify ECG signals after normalizing data by using StandardScalar approach
* For each ECG signal, 169 features have been extracted and there are four classes in total indicated by N, A, O, ~
* In the next part, another 4-layer MLP network was trained to detect whether an ECG signal is normal or abnormal
### Q7
* Implementing MADALINE networks with 3 and 6 neurons in the last layer
* There are two classes of points:
    * class 1: 100 points within a circle with center (0, 0) and radius of 1 
    * class 2: 100 points in the restricted area between two circles with the same center (0, 0) and radii of 1.3 and 1.6
### Q8
* Implementing deep CNN for classifying cifar10 images (containing 60000 images in 10 classes)
* Training the model with Adam, SGD and rmsprop solvers
* The architecture of the mentioned CNN is:

| Layers        | Layers Parameter     | Activation Function  |
| ------------- |:--------------------:| --------------------:|
| conv2D        | 32, size(3,3)        | Relu                 |
| conv2D        | 32, size(3,3)        | Relu                 |
| conv2D        | 32, size(3,3)        | Relu                 |
| Maxpooling2D  | size(2,2)            | -                    |
| Droupout      | 0.25                 | -                    |
| conv2D        | 64, size(3,3)        | Relu                 |
| conv2D        | 64, size(3,3)        | Relu                 |
| conv2D        | 64, size(3,3)        | Relu                 |
| Maxpooling2D  | size(2,2)            | -                    |
| Droupout      | 0.25                 | -                    |
| Dense         | 512                  | Relu                 |
| Droupout      | 0.5                  | -                    |
| Dense         | 10                   | Softmax              |

### Q9
* Implementing a Decision Tree classifier on Diabetes.csv dataset
* In the next part, implementing a Decision Tree with maximum depth of 2
