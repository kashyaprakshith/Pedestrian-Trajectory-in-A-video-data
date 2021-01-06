# Social LSTM using PyTorch



> Rakshith Raghavendra Kashyap. ** Pedestrian Trajectory in a video data**. 


## Requirements
* Python 3
* Seaborn (https://seaborn.pydata.org/)
* PyTorch (http://pytorch.org/)
* Numpy
* Matplotlib
* Scipy

## How to Run
* Before running the code, create the required directories by running the script `make_directories.sh`
* To train the model run `python social_lstm/train.py` (See the code to understand all the arguments that can be given to the command)
* To test the model run `python social_lstm/sample.py --epoch=n` where `n` is the epoch at which you want to load the saved model. (See the code to understand all the arguments that can be given to the command)
