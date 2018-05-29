# Novel-Deep-Learning-Model-for-Traffic-Sign-Detection-Using-Capsule-Networks
capsule networks that achieves outstanding performance on the German traffic sign dataset

paper link
https://arxiv.org/abs/1805.04424

Abstract
----
Convolutional neural networks are the most widely used deep learning algorithms for traffic signal classification till date but they fail to capture pose, view, orientation of the images because of the intrinsic inability of max pooling layer.This paper proposes a novel method for Traffic sign detection using deep learning architecture called capsule networks that achieves outstanding performance on the German traffic sign dataset.Capsule network consists of capsules which are a group of neurons representing the instantiating parameters of an object like the pose and orientation by using the dynamic routing and route by agreement algorithms.unlike the previous approaches of manual feature extraction,multiple deep neural networks with many parameters,our method eliminates the manual effort and provides resistance to the spatial variances.CNNs can be fooled easily using various adversary attacks and capsule networks can overcome such attacks from the intruders and can offer more reliability in traffic sign detection for autonomous vehicles.Capsule network have achieved the state-of-the-art accuracy of 97.6% on German Traffic Sign Recognition Benchmark dataset (GTSRB).

you can download the dataset from the below link
--------------
https://drive.google.com/open?id=1zzOP3Kg4SIOyYmh89yOF9PeEEpALxh_k

steps to run
------------
1)Install all the dependencies \
Tensorflow,Keras,Numpy,Pandas,Pickle,Matplotlib \
2)Run the ipython notebook file Traffic_Sign_Classifier-Copy1.ipynb using jupyter notebook 

you can cite this paper if you are using this code for your research
------
@article{kumar2018novel, \
  title={Novel Deep Learning Model for Traffic Sign Detection Using Capsule Networks}, \
  author={Kumar, Amara Dinesh}, \
  journal={arXiv preprint arXiv:1805.04424}, \
  year={2018} \
}

MIT License

Copyright (c) 2018 Dinesh Kumar Amara

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
