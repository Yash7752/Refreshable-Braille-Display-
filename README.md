
# Refreshable Braille Display

This project focuses on developing a **Refreshable Braille Display**, a device that allows visually impaired individuals to read Punjabi language books in Braille. The aim is to create a **cost-effective** and **portable** solution that assists users in self-paced learning and helps convert regional languages into Braille.

## Features
- **Self-paced Learning Interface**: The display allows individuals to learn at their own speed.
- **Braille Conversion**: Converts text from regional languages into Braille format for display.
- **Portable & Cost-effective**: Designed to be affordable and easy to carry, making it accessible for wider use.

## Project Structure
```
Refreshable-Braille-Display/
│
├── image_dataset/          # Contains images used for training and testing the model
├── braille-file-x.x.ipynb   # Jupyter notebook files with model code
├── dat_to_grayscale.ipynb   # Converts .dat files to grayscale images for processing
└── README.md               # Documentation file
```

## Technologies Used
- **Python**
- **TensorFlow** for model training and classification.
- **Keras** for building deep learning models.
- **NumPy** for data manipulation.
- **PIL** (Pillow) for image processing.
- **Git** for version control.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Yash7752/Refreshable-Braille-Display-.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Refreshable-Braille-Display
   ```
3. Run the Jupyter notebook to start the model training process:
   ```bash
   jupyter notebook
   ```

## Dataset
The dataset includes images of regional language characters converted to Braille. The data is preprocessed using grayscale conversion techniques and fed into a neural network model for classification.

## Results
The trained model achieves an accuracy of over 90% in predicting Braille characters from regional languages. Fine-tuning using a pre-trained model such as VGG16 further enhances accuracy.

## Future Work
- **Real-time text-to-Braille conversion** using camera input.
- **Improved hardware integration** for tactile display.
- **Support for additional regional languages** beyond the initial scope.

## Contributing
Feel free to submit pull requests or open issues to improve the project. Contributions are welcome!

