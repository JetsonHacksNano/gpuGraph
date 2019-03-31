# gpuGraph
A very simple moving graph of GPU activity for the NVIDIA Jetson Nano Developer Kit. This allows visualization of GPU utilization.

![GPU Activity Window](https://github.com/jetsonhacks/gpuGraph/blob/master/gpuGraph.png)

The graph is implemented as an animated Python Matplotlib graph. The app requires the Python Matplotlib library.

For Python 2.7, Matplotlib may be installed as follows:

$ sudo apt-get install python-matplotlib

For Python 3, Matplotlib may be installed as follows:

$ sudo apt-get install python3-matplotlib

You can run the app:

$ ./gpuGraph.py

or:

$ python gpuGraph.py

or:

$ python3 gpuGraph.py

<h2>Release Notes</h2>

Initial Release March, 2019
* L4T 232.1.0 (JetPack 4.2)
* Tested on Jetson Nano Developer Kit

