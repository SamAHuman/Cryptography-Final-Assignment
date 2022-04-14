

* **Required packages for SecureNN:**
  * [`g++`](https://packages.debian.org/testing/g++)
  * [`make`](https://packages.debian.org/testing/make)
  * [`libssl-dev`](https://packages.debian.org/testing/libssl-dev)
.


### data download
DOwnload from this link
https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection
ANd extract it using feature_extraction.ipynb

#### Repository Structure

* `files/`    - Shared keys, IP addresses and data files.
* `lib_eigen/`    - [Eigen library](http://eigen.tuxfamily.org/) for faster matrix multiplication.
* `mnist/`    - Parsing code for converting MNIST data into SecureNN format data.
* `src/`    - Source code for SecureNN.
* `utils/` - Dependencies for AES randomness.

#### Building SecureNN

To build SecureNN, run the following commands:

```
git clone https://github.com/snwagh/SecureNN.git
cd SecureNN
make


#### Running SecureNN
Run this command
./BMRPassive.out STANDALONE 4 files/parties_localhost files/keyA files/keyAB files/data/train_sample_feature.csv files/data/train_sample_labels.csv files/data/test_sample_features.csv files/data/test_sample_labels.csv 
```
```



\
