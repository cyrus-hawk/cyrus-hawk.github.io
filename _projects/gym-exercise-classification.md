---

name: Gym exercise classification

description: >
    Employing multimodal data fusion techniques to classify the type
    of exercise an athlete is performing.

title: Gym exercise classification

img_loc: /assets/images/gym-exercise-classification/page_intro.png

---

# Introduction

We are interested in classifying various types of exercises performed
by individuals to build an athletic app. This project specifically
focuses on the classification aspect. The recorded seven different
exercises performed by athletes using wearable sensors and a depth
camera can be found in the dataset available at <a
href="https://archive.ics.uci.edu/ml/datasets/MEx#"
target="_blank">this link</a>. To recognize the type of activity
performed by the athletes, I utilize my knowledge of multimodal data
fusion by combining data from the depth camera and multiple wearable
sensors.

# Final result

The following tasks have been conducted to derive the final results and classifications:

* Data munging (pre-processing)
* Feature extraction and unimodal fusion for classification
* Feature extraction and feature-level fusion for multimodal classification
* Decision-level fusion for multimodal classification

## Classification using Support Vector Machine (SVM)

### Classification based on the accelerometer sensor

![](/assets/images/gym-exercise-classification/4.3.2.png)

This classifier performs better in identifying exercises 01, 04, and
05 compared to other exercises. However, exercises 03 and 06 are the
most misclassified exercises.

### Classification based on the depth camera sensor

![](/assets/images/gym-exercise-classification/4.3.3.png)

Almost all exercises, except exercise 06, are correctly recognized
when using the data from the depth camera sensor.

## Classification using AdaBoost

### Classification based on the accelerometer sensor

![](/assets/images/gym-exercise-classification/4.3.4.png)

Exercises 03 and, to some degree, 05 are the two exercises that are
most consistently recognized compared to others when using AdaBoost on
accelerometer data.

### Classification based on the depth camera sensor

![](/assets/images/gym-exercise-classification/4.3.5.png)

Exercises 03, 04, and 05 are the exercises that are most accurately
classified compared to others when using AdaBoost on depth camera
data.

## Conclusion

When using classification rules, we observe that SVM produces better
results. This can also be intuitively observed by examining the
confusion matrices.

![](/assets/images/gym-exercise-classification/4.3.1.png)
