# Toptag Model

## Training and Testing data
[The binary classifier training and testing data are stored here](https://cernbox.cern.ch/index.php/s/0CBn5SsUPb5KDnX)

* `x_train.npy` :Training input features. This is a 3D array. For each event there are 20 particles and for each particle there six variables.
* `y_train.npy` : Contains 5 class labels for each event. Use the 5th column for training and testing purpose.
* `x_test.npy` : Testing features. Same format as the training data.
* `y_test.npy` : Same as the training data. Use the 5th column for testing.

## Training and testing scrips
All the training and testing scripts are inside the `hls4ml-rnn-toptag` directory

# B-tagging Model

## Training and Testing data
Dataset is based on 7 TeV ttbar MC of CMS Open Data. You can download it here:
`https://cernbox.cern.ch/index.php/s/dYrWPhWQFbAgjh1 - pwd: hls-btag`

## Training and testing scrips
All the training and testing scripts are inside the `hls4ml-rnn-btag` directory
