# BIDMach_Caffe
Integrate **Caffe** with BIDMach using **JavaCPP**

##### [Caffe](https://github.com/BVLC/caffe):
Caffe is a Deep Learning library built by Berkeley Vision and Learning Center, written primarily in C++. 

##### [JavaCPP](https://github.com/bytedeco/javacpp):
JavaCpp provedes efficient access to native C++ inside Java. It already provides [presets](https://github.com/bytedeco/javacpp-presets/tree/master/caffe) for Caffe.

###Task:
We want to integrate **Caffe** with BIDMach using **JavaCPP**, for a few reasons. 

First, it takes up to a few days for an experienced devleoper to build a working verison of Caffe and its dependencies. The integration will provide a much easier access to Caffe from BIDMach. 

Second, users of Caffe could take adavantage of features of BIDMach. Users of BIDMach would be able to access Caffe, a widely used Deep Learning library.

To achivie this, we will use JavaCPP, the advantages of which is documented in its own repository. The fact that caffe presets is provided makes life even easier! With the presets, JavaCPP will most likely auto-parse the C++ files of Caffee and generate Java code for us, as it is shown [here](https://github.com/bytedeco/javacpp-presets/tree/master/caffe#sample-usage).
