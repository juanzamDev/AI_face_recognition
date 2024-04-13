# Facial Recognition System

## Project Overview
This project implements a facial recognition system using Python. It includes scripts for capturing faces, training a recognition model, and performing facial recognition. The system utilizes an LBPH (Local Binary Patterns Histograms) face recognizer to efficiently recognize faces in real-time.

## Files Description
- `capturandoRostros.py`: Script to capture face images and prepare training data.
- `entrenandoRF.py`: Script to train the facial recognition model using the captured data.
- `modeloLBPHFace.xml`: Pre-trained LBPH model for facial recognition.
- `ReconocimientoFacial.py`: Main script that uses the trained model to recognize faces from a live video feed.

## Prerequisites
Before running this project, ensure you have the following installed:
- Python 3.x
- OpenCV library
- NumPy

You can install the necessary Python libraries using pip:
```bash
pip install opencv-python-headless numpy
```

## Installation
Clone the repository to your local machine:
```bash
git clone <repository-url>
cd <repository-name>
```

## Usage
Follow these steps to run the facial recognition system:

1. **Capture Training Data:**
   Run the `capturandoRostros.py` to capture face images for training the model.
   ```bash
   python capturandoRostros.py
   ```

2. **Train the Model:**
   After capturing enough face images, run `entrenandoRF.py` to train the facial recognition model.
   ```bash
   python entrenandoRF.py
   ```

3. **Run Facial Recognition:**
   With the model trained, start the facial recognition script.
   ```bash
   python ReconocimientoFacial.py
   ```

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your improvements.

## License
Specify the license under which the project is released, such as MIT, GPL, etc.
