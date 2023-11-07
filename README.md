# Image Caption Generation - LSTM-CNN

This project focuses on generating captions for images using LSTM (Long Short-Term Memory) and CNN (Convolutional Neural Network) models. The dataset used for training and evaluation is the Flickr8K dataset, which can be accessed through the following link: [Flickr8K Dataset](https://www.kaggle.com/account/login?titleType=dataset-downloads&showDatasetDownloadSkip=False&messageId=datasetsWelcome&returnUrl=%2Fdatasets%2Fadityajn105%2Fflickr8k%2Fversions%2F1%3Fresource%3Ddownload).

## Dataset

The Flickr8K dataset consists of 8,000 images collected from the Flickr website. Each image in the dataset is accompanied by five captions describing the content of the image. The dataset is widely used for image caption generation research and evaluation. It provides a rich resource for training models to generate descriptive and contextually relevant captions for images.


## Project Structure

The project has the following file structure:

- `image_caption_generation.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and caption generation.
- `README.md`: Documentation file providing an overview of the project.

## Getting Started

To get started with this project, follow the steps below:

1. Clone this repository to your local machine or download the project files.
2. Access the [Flickr8K Dataset](https://www.kaggle.com/account/login?titleType=dataset-downloads&showDatasetDownloadSkip=False&messageId=datasetsWelcome&returnUrl=%2Fdatasets%2Fadityajn105%2Fflickr8k%2Fversions%2F1%3Fresource%3Ddownload) using the provided link and download the dataset files.
3. Extract the dataset files and place them in a directory named `data` within the project folder.
4. Open the Jupyter Notebook `image_caption_generation.ipynb` using Jupyter Notebook or any compatible environment.
5. Ensure that you have the necessary dependencies installed, including Python, TensorFlow, Keras, and other required libraries.
6. Run the code cells in the Notebook sequentially to preprocess the data, train the LSTM-CNN models, and generate captions for test images.
7. Feel free to modify the code or experiment with different model architectures and hyperparameters to improve the caption generation performance.

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib

You can install the required dependencies using pip:

```
pip install tensorflow keras numpy pandas matplotlib
```

## License

The Flickr8K dataset used in this project is subject to the terms and conditions specified by the dataset provider. Please refer to the Kaggle website and the dataset's license for more information.

The project code is released under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgments

- Kaggle for providing the Flickr8K dataset.

## Further Help

If you encounter any issues or have questions regarding the project, please feel free to [open an issue](https://github.com/SarahEldreny/image-caption-generation-lstm-cnn/issues) in the project repository.
