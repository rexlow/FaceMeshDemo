## Face Mesh with iOS ARKit + SceneKit

So I was exploring ways to deploy face landmark detector onto a mobile environment. The only way I know how was to either deploy with [Tensorflow Lite](https://www.tensorflow.org/lite) or [PyTorch Mobile](https://pytorch.org/mobile/home/).

Both of them are great in terms of inference speed and accuracy, but nothing beats the native SDK! Check out the [Face API from Apple here](https://developer.apple.com/documentation/arkit/content_anchors/tracking_and_visualizing_faces)

The advantages of ARKit over custom ML models here being:

1. Ultra fast inference speed
2. Short warmup time
3. Buttery smooth animation
4. Less than 50 lines of code! And no machine learning knowledge needed!

Disadvantages:

1. Only supports devices from iPhone X and above
2. It is not portable for Android counterparts. It means for business purposes, it is not possible to deliver the same experience for our customers using Android devices :(

Demo video :)


https://user-images.githubusercontent.com/7680796/117015608-79debb00-ad24-11eb-9a12-1d91006083af.mov

