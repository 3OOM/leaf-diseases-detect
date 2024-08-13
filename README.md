
# Leaf Diseases Detection

This project is designed to detect diseases in plant leaves using machine learning and image processing techniques. By leveraging the power of Flask and TensorFlow, this tool aims to help farmers and gardeners maintain healthy crops through early disease detection.

## Demo Video

![Demo Video](media/OutputFile.gif)


The GIF above demonstrates the detection process in action.

## Features

- **Image Upload**: Easily upload images of leaves to detect potential diseases.
- **Disease Classification**: Accurately classify leaf diseases based on the uploaded image.
- **Results Visualization**: Provides clear results with disease information and suggested remedies.
- **User-Friendly Interface**: Simple and intuitive interface for users of all levels.
 
## Creating the `.h5` File

To generate the necessary `.h5` file for the Leaf Diseases Detection project, follow these steps:

### Step 1: Run any one file mentioned in "Dataset train python files" folder
### Step 2: After successfully run file you get the .h5 file based on model file which you run
### Step 3: Just copy that file in project folder here (leaf-diseases-detection/)

## .pkl File is Provided 
Ensure you have all required dependencies installed.
- **Important**: If you have low specs in your machine then the process takes time.
- **I'm providing pickle file(model_vgg16.pkl and model_inception.pkl) just copy into project directory**


## Dataset

The dataset used for training the model can be found on Kaggle: [Leaf Disease Dataset](https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf)
Over 10 Thousand + tomato leaves images.
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/3OOM/leaf-diseases-detection.git
   
   cd leaf-diseases-detection
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from Kaggle and place it in the appropriate directory.

4. Run the application:
   ```bash
   python app.py
   ```

## Requirements

The project dependencies are listed in the `requirements.txt` file. Install them using pip:

```bash
pip install -r requirements.txt
```

## Usage

1. Launch the application.
2. Upload an image of a leaf.
3. Click on "Detect" to see the disease classification and related information.
4. View the results and suggested remedies.

## Technologies Used

- **Python**: Core programming language.
- **Flask**: Backend framework for handling requests and rendering responses.
- **TensorFlow**: Machine learning framework for model training and prediction.
- **OpenCV**: Image processing library.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
