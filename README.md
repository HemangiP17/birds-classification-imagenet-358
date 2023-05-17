# Birds vs. Squirrels Classification Model
This repository contains code for training a deep learning model to classify images of birds and squirrels using TensorFlow. The model architecture is based on the Xception convolutional neural network, pretrained on the ImageNet dataset.

## Requirements
To run the code in this repository, you need the following dependencies:

TensorFlow (version 2.0 or higher)
Matplotlib (for visualization)
Pandas (for data handling)
Dataset
The training and validation datasets are stored in TFRecord format. The training dataset is located at ./datasets/birds-20-eachOf-358.tfrecords, and the validation dataset is located at ./datasets/birds-10-eachOf-358.tfrecords.

Model Architecture
The model architecture is based on the Xception convolutional neural network, pretrained on the ImageNet dataset. The last fully connected layer is replaced with a dense layer with 358 units, representing the number of classes in the dataset (birds and squirrels). The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss.

For more details on the model architecture, refer to the model.summary() output in the code.

## Results
The training history and accuracy plot are saved in the results directory. The training loss, training accuracy, validation loss, and validation accuracy are plotted over the training epochs.

## License
This project is licensed under the MIT License.

## Acknowledgments
The Xception model and its weights are provided by the TensorFlow Keras library, based on the original paper:

<ul>
<li>Chollet, F. (2017). Xception: Deep Learning with Depthwise Separable Convolutions. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR) (pp. 1800-1807).</li>
</ul>
  
## Contributing
Contributions to this project are welcome. Feel free to fork the repository and submit a pull request.

If you have any questions or suggestions, please open an issue or contact the project maintainers.

## Authors
Hemangi Patel hemangipatel171998@gmail.com or hp493@drexel.edu
  
References
Include any references or resources that were used in the development of this project.

## TensorFlow Documentation
1. [Keras Documentation](https://keras.io/api/) 
2. [Matplotlib Documentation](https://matplotlib.org/stable/tutorials/index.html) 
3. [Pandas Documentation](https://pandas.pydata.org/docs/reference/series.html/) 
