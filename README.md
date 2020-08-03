<h1>ABSTRACT</h1>

A2E is a CNN based system which coverts static hand gestures of the American Sign Language to English Text. A2E aims to solve reduce the communication between a average person and a differently-able person.

It uses various libraries like <b>TensorFlow (Keras)</b>, <b>scikit-learn</b>, <b>OpenCV</b>, etc for different purposes. Concepts used are CNN, Data Augmentation and Transfer Learning.

A2E does the conversion in real time.

<h1>DATA COLLECTION AND CLEANING</h1>

We tried to collect data from 50 diffrent people, after few week of hard work we were able to do so.... BUT.... the data we collected turned out to be VERY noisy and basically unuseable. So we had to come up with a diffrent solution.

Hence, the "webcam data.ipynb" notebook. We used this notebook to take and save pictures using <b>OpenCV</b>. We took arount 50 pictures for each alphabets of shape (200,200,3). No further cleaning was required as the pictures taken were in pretty good condition.

<h1>DATA AUGMENTATION AND PREPROCESSING</h1>

The amount of data we had was not enough to counteract overfitting and decent genrealization. So we had to use data augmentation. We used the <br>ImageDataGenerator</br> class for this purpose. The training data was allowed to me augmented in various ways, but the validation and test data only went through Normalization ( division by 255 ).

<h1>SHALLOW CNN MODEL</h1>

Coming soon

<h1>TRANSFER LEARNING</h1>

Coming soon

<h1>CONCLUSION AND FINAL OUTCOME</h1>

Coming soon
