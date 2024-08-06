# Gesture-Recognition-and-Control 👋🏻

Gesture-Recognition-and-Control👋🏻 is a gesture recognition system for managing YouTube playback using hand movements. It allows users to execute actions such as play/pause and volume adjustments with simple, intuitive gestures.

## Table of Contents 📚
- Features
- Data Source
- Installation
- Usage
- Contributing
- License

## Features 👨🏻‍💻

- **YouTube Control**: Use hand gestures to control YouTube playback, including actions like play/pause and volume adjustments.
- **Real-Time Recognition**: The Python script facilitates live gesture recognition using a webcam.
- **Model Training**: Use the provided Jupyter notebook to train your own gesture recognition model.
- **Gesture Data Capture**: Effortlessly capture and record gesture data using the web interface.

## Data Source 💾

The project leverages webcam-captured data to train the model. The dataset is created using the provided HTML interface to record hand gestures, which are subsequently used to train the recognition model.

## Installation 📲

To get started with Wave Control, follow these steps:

1. Clone the repository.
2. Navigate to the project directory.
3. Install the required dependencies.
4. Run the `.html` file to create the dataset.
5. Train the recogntion model on the custom dataset by running the `.ipynb` notebook.

```bash
   jupyter notebook Gesture Recognition.ipynb
   ```

7. Start the application.

```bash
   python3 main.py
   ```

## Usage 🛒

### HTML File 📸

1. Open the HTML file (`index.html`) in a web browser.
2. Follow the on-screen instructions to capture and save gesture images for training.
3. Create a main folder `Gestures` and create 4 sub-folders - `Nothing`, `Play`, `VolumeDown`, `VolumeUp` - and include the gesture images in their respecive sub-folders.
   
### Jupyter Notebook 🖥️

1. Open `Wave Control.ipynb` in Jupyter Notebook or JupyterLab.
2. Follow the instructions within the notebook to develop your own gesture recognition model.

### Python Script 💻

1. Execute the Python script (`main.py`) to start the real-time gesture recognition.
2. Use hand gestures to control YouTube playback (play/pause, volume up/down).

## Contributing 💡

Welcoming and encouraging contributions to enhance this project! If you have any ideas for improvement or come across any issues, please don't hesitate to open an issue or submit a pull request. Your contributions are highly valued and appreciated.

## License ⚖️

This project is distributed under the MIT License. You can find detailed information about the licensing terms in the [LICENSE](LICENSE) file.
