#  To Comprehend the New: On Measuring the Freshness of a Document by Tirthankar Ghosal, Abhishek Shukla, Asif Ekbal and Pushpak Bhattacharyya accepted as a full paper in the 37th International Joint Conference on Neural Networks (IJCNN 2019) to be held at Budapest, Hungary (CORE rank A/H-Index: 31).


## Requirements
* Infersent (https://github.com/facebookresearch/InferSent): Infersent is used for training a sentence encoder on SNLI corpus.
* PyTorch (for training the sentence encoder and inferring sentence embeddings)
* Keras


## Description of important files in each directory
* `input_generation.py` Produces pre-trained sentence embeddings for dlnd data also produces document matrix based on sentence embeddings for input to CNN.
* `model.py` This is the main CNN program.It creates the output file which has the predictions for each target and source document pair.

* `TAPNew.zip` This is training Data.
