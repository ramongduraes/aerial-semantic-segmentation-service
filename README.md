# aerial-semantic-segmentation-service
Semantic Segmentation for Aerial Images - SingularityNET Service


Original work: https://github.com/mitmul/ssai-cnn/blob/master/LICENSE


Trying to build a container from scratch:
```bash
apt-get update
apt-get install -y wget git python3.5 python3-pip #python3.5.2 pip 8.1.1

pip3 install --upgrade pip

pip install cython==0.23.4 numpy==1.10.1 tqdm
pip install 

```




Trying with closest chainer image:  v2.0.0-python3
```bash
apt-get update
apt-get install -y git wget

pip3 install --upgrade pip
pip install --upgrade setuptools
pip install cython==0.23.4 tqdm lmdb==0.87

# Boost 
wget http://sourceforge.net/projects/boost/files/boost/1.59.0/boost_1_59_0.tar.gz
tar -xvzf boost_1_59_0.tar.gz


# Boost.Numpy
git clone https://github.com/ndarray/Boost.NumPy.git
cd Boost.Numpy
git reset --hard 26aaa5b



```

