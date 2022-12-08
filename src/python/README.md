# B-tagging Model

## Training and Testing data
Dataset is based on 7 TeV ttbar MC of CMS Open Data. You can download it [here](https://cernbox.cern.ch/index.php/s/dYrWPhWQFbAgjh1) `- pwd: hls-btag`

## Training and testing scrips
All the training and testing scripts are inside the `hls4ml-rnn-btag` directory

# Toptag Model

## Training and Testing data
The binary classifier training and testing data are stored [here](https://cernbox.cern.ch/index.php/s/0CBn5SsUPb5KDnX)

* `x_train.npy` :Training input features. This is a 3D array. For each event there are 20 particles and for each particle there six variables.
* `y_train.npy` : Contains 5 class labels for each event. Use the 5th column for training and testing purpose.
* `x_test.npy` : Testing features. Same format as the training data.
* `y_test.npy` : Same as the training data. Use the 5th column for testing.

## Training and testing scrips
All the training and testing scripts are inside the `hls4ml-rnn-toptag` directory

# Quickdraw Model

## Training and Testing data
 
The training and testing data need to be produced by running the file `Quickdraw Preprocess.ipynb`.
You can download the needed data for creating our training and testing dataset in [here](https://console.cloud.google.com/storage/browser/quickdraw_dataset/sketchrnn;tab=objects?pli=1&prefix=&forceOnObjectsSortingFiltering=false)

## Training and testing scrips
The training and testing scrips are already inside the `hls4ml-rnn-quickdraw` directory.
