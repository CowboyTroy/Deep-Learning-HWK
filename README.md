# Deep-Learning-HWK

In this excercise, I utilized Tensorflow to perform the deep learning models for Bitcoin in both the historic pricing context and the "Fear and Greed" approach. It was very intersting to build both models for the comparison and here were my results:

Which model has a lower loss?
The RNN model had a lower loss (0.0487) than the FNG model (.1911).

Which model trackes the actual values over time?
The RNN model tracks actual values over time vs. the FNG model tracking the index created from outside sources other than price.

Which window size works best for both models?
Based on the real vs. predicted plot, it would appear the FNG model works best over time with a much higher variation between the two.
