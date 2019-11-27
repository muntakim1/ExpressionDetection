# ExpressionDetection

Tensorflow for poets is a <strong>Image classifier</strong> introduced in Google Summit 2016. With this classifier example we can detect flowers.
I have changed this code little bit and make it able to detect human expression with the help of youtube and stackoverflow.

# Install required Dependencies.

``` pip install -r requirements.txt ```

# Create a image directory where do you put your images.

``` 
    mkdir images
    
    cd images
    
    mkdir Happy
    
    mkdir Sad
```

now put images into the folders Sad or cry images into Sad folder and Happy or smiling photos into the Happy folder

# Train classifier.

``` python train.py ```

<em>It will take some time.</em>

# Start Label.py

``` python label.py ```


# More about Inception V3 architecture.

![alt text](https://miro.medium.com/max/960/1*gqKM5V-uo2sMFFPDS84yJw.png)


# For Learn more

* [Inception V3](https://medium.com/@sh.tsang/review-inception-v3-1st-runner-up-image-classification-in-ilsvrc-2015-17915421f77c)
* [Tensorflow for poets](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/#5)
