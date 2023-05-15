
# NeuraLipNet

LipNet is a deep learning model that can recognize words from the movement of the lips in a video. It is based on a combination of convolutional and recurrent neural networks and was originally proposed in a paper by Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas. 

## Installation

To use LipNet, you will need to have Python 3 installed on your machine, along with several additional packages, including TensorFlow and OpenCV. You can install these dependencies by running the following command:

```bash
pip install -r requirements.txt
```

In addition, you will need to download the pre-trained weights for the model, which are available [here](https://drive.google.com/open?id=1ycUyj6myMsrMq3mJTW-6azUKGveCY53K). Once you have downloaded the weights, you should save them in the `models` directory.

## Usage

To use LipNet, you can run the `predict.py` script, which will take a video file as input and output the recognized words. For example:

```bash
python predict.py video.mp4
```

By default, the script will use the pre-trained weights that were downloaded earlier. If you want to use your own trained model, you can specify the path to the weights file using the `--weights` argument:

```bash
python predict.py video.mp4 --weights /path/to/weights.h5
```

## License

This implementation of LipNet is released under the MIT License. Please see the `LICENSE` file for more information.

## Acknowledgments

This implementation is based on the work of Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas. The implementation by Nick Bourdakos was used as a starting point for this repository.

![Output](https://github.com/Shubhajaiswal/Neuralipnet/assets/72022772/86cc271c-b031-47c1-bf4d-cd75762161a2)

