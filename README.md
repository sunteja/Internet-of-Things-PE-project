# Heart Disease prediction of UCI dataset using ML with Homomorphic encryption using TenSEAL

## Introduction
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With the increasing number of heart diseases day by day, detecting and preventing heart diseases as early as possible has become a necessity for us. Moreover, good data systems can improve the research in heart diseases prevention and can improve and save many people's lives. <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Hence, for these purposes, we can use ML to create a model (Naive Bayes classification model) and predict whether a person will suffer from any heart diseases in the future or not based on various parameters in the given data. <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;However, the problem with the normal models is that many patients wouldn't want to expose their data (especially health data) to other people (or to the person running the model either) which is why we use encryption so that there are no unauthorized accesses of data. For this an encryption called Homomorphic encryption is used. Homomorphic encryption is an encryption in which all the data is converted into ciphertext or encrypted data and ML models are applied on this ciphertext without decrypting the data. The final results are also given in ciphertext only. So, even the model owners won't have an idea about what kind of data is being processed by their models.<br /> <br />
Please download the dataset from [here](https://www.kaggle.com/johnsmith88/heart-disease-dataset). <br/> <br/>

## What is TenSEAL?
TenSEAL is a tool used for implementing fully homomorphic encryption. It is basically a python wrapper built over Microsoft SEAL which is a C++ library implementing the BFV and CKKS homomorphic encryption schemes. The python wrapper keeps the C++ implementation inside the wrapper and because of this we can use this library with our python models in machine learning. <br/> <br/>

## Installing TenSEAL
* Before installing TenSEAL, make sure that the latest version of the PyPy library is installed. If you are using a MacOS then, you can install PyPy by running the following two commands in a terminal `
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py` and `sudo python get-pip.py` commands. If you are not using a MacOS then, just directly download the PyPy library from [here](https://www.pypy.org/download.html). You can find the MacOS version of PyPy here too. Make sure you download the recent most version of it. 
* After installing PyPy, for installing TenSEAL, please refer to the instructions given [here](https://github.com/OpenMined/TenSEAL/blob/main/README.md). Please go through the tutorial section to learn how to use this library for homomorphic encryption. <br/> <br/>