# Hand Shape Recognition
## Description - Hand Shape Recognition Using Hand Marker Tracking
The Vicon motion capture camera system was used to capture 15 users performing 5 hand postures. The motion capture system consists of a network of intricate cameras. 

To be able to capture hand postures, the motion capture system requires users to attach specific markers to their hand. Markers were attached to a glove which users were able to wear. The system then uses these markers together with the system of intricate cameras to find and precisely locate the markers (on the hand) in space i.e. an X, Y and Z location for each marker.

The markers are the small white dots on the glove. The majority of these markers (all of the markers except those on the tips of the fingers) were used to create a local coordinate system for the hand to get a localized X,Y and Z coordinate for the five markers on the tips of the fingers. Therefore, the features provided in this data set are the X, Y and Z coordinates of the tips of the fingers (3 coordinates × 5 fingers = 15 features) with respect to the palm of the hand. The goal of this project is to therefore make use of these features to try to predict the posture of the hand.

The users performed five hand postures in total i.e.:

`1 → 	Fist (with thumb out)`

`2 → 	Stop (Hand flat)`

`3 → 	Point 1 (Fist with index finger out)`

`4 → 	Point 2 (First with index and middle fingers out)`

`5 → 	Grab/Claw (Fingers curled as if to grab)`

## Techniques

`Support Vector Machines`:

Use the sklearn implementation of SVMs. Use the Gaussian (aka Radial-Basis Function) kernel only.

`Neural Networks`:

Use the sklearn implementation of NNs. Use a three-layer NN with one input, one hidden and one output layer.

`Logistic Regression`:

Use the sklearn implementation of Logistic Regression. As you know, the machinery of Logistic Regression allows for a large number of different feature variations e.g. higher-order features and/or combination of features. 

## File Run Order
[Dividing Data (dividing_data.ipynb)](https://github.com/MTashreeqWaggie/Hand-Shape-Recognition/blob/main/Dividing%20Data/dividing_data.ipynb)

[Logistic Regression (train_logistic_regression.ipynb)](https://github.com/MTashreeqWaggie/Hand-Shape-Recognition/blob/main/train_logistic_regression.ipynb)

[Support Vector Machines (train_support_vector_machines.ipynb)](https://github.com/MTashreeqWaggie/Hand-Shape-Recognition/blob/main/train_support_vector_machines.ipynb)

[Nueral Network(train_neural_network.ipynb)](https://github.com/MTashreeqWaggie/Hand-Shape-Recognition/blob/main/train_neural_network.ipynb)

[Testing (testing.ipynb )](https://github.com/MTashreeqWaggie/Hand-Shape-Recognition/blob/main/testing.ipynb)

[Demo (demo.ipynb)](https://github.com/MTashreeqWaggie/Hand-Shape-Recognition/blob/main/demo.ipynb)

## Contributors

[Tashreeq Waggie]() - Logistic Regression , Support Vector Machines and Testing 

[Jared Cupido]() - Dividing Data , Neural Networks and part of Demo
