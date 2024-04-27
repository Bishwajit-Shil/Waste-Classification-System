# Real-time Waste Classification

This Python script implements a real-time waste classification system using a webcam. It captures video from the webcam, processes each frame to classify waste, and overlays the appropriate waste and bin images based on the classification result.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- cvzone (`pip install cvzone`)

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/your_repository.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your_repository
   ```

3. Run the script:

   ```bash
   python waste_classification.py
   ```

4. Press `Esc` key to exit the program.

## Description

- `waste_classification.py`: This is the main Python script that captures video from the webcam, processes each frame, and overlays waste and bin images based on the classification result.

## File Structure

- `Resources/Model/keras_model.h5`: Pre-trained CNN model for waste classification.
- `Resources/Model/labels.txt`: Text file containing class labels for the model.
- `Resources/arrow.png`: Image of an arrow used for visualization.
- `Resources/background.png`: Background image for overlaying waste and bin images.
- `Resources/Waste/`: Directory containing waste images.
- `Resources/Bins/`: Directory containing bin images.

## Acknowledgements

- This project utilizes the `cvzone` library for overlaying images on the background.
- The waste classification model is based on a pre-trained CNN model.
- Waste and bin images are sourced from various online repositories.

