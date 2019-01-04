# tensorflow
how to import tensorflow under python 3.6


https://blog.csdn.net/yz960611/article/details/78538488
注意 第4步 打开cmd, 进入该路径， 输入 pip install tensorflow-1.9.0-cp36-cp36m-win_amd64.whl 
这是在python IDLE 中运行 tensorflow



Anaconda 安装 Tensorflow  http://blog.51cto.com/acevi/2103437
  conda create -n tensorflow python=3.6
  pip install tensorflow
这里载入的是 1.12.0 tensorflow 

ImportError：No module named 'tensorflow'？
pip install --upgrade -I setuptools
pip install --upgrade --ignore-installed tensorflow
出现 “distributed 1.21.0 requires msgpack, which is not installed”
run this command 
conda install -c anaconda msgpack-python
或者 pip install msgpack
