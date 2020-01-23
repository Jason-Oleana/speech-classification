# Speech classification

In this challenge the task is to learn to recognize which of several English words
is pronounced in an audio recording. This is a multiclass classification task.

## Requirements

tensorflow
keras
imblearn

## Data files

• wav.tgz: a compressed directory with all the recordings (training and test
data) in the form of wav files.

• train.csv: this file contains two columns: path with the filename of the
recording and word with word which was pronounced in the recording.
This is the training portion of the data.

• test.csv: This is the testing portion of the data, and it has the same
format as the file train.csv except that the column word is absent.
