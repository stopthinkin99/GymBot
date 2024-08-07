# Gymbot: Real-Time Exercise Identification and Form Improvement

## Overview
Gymbot is a real-time gym assistant designed to help users identify exercises and improve their form using machine learning. By leveraging LSTM models, OpenCV, and MediaPipe, Gymbot captures and analyzes video streams, providing immediate feedback to enhance workout efficiency and safety.

## Features
- **Real-Time Video Capture**: Uses OpenCV to capture video streams in real-time.
- **Exercise Identification**: Employs an LSTM model integrated with MediaPipe to recognize various exercises.
- **Form Improvement Feedback**: Provides actionable insights and recommendations to help users improve their exercise form.

## Project Structure
- **gymrefinedmodel.ipynb**: Jupyter Notebook containing the main code for the project, including model training, video capture, and form feedback functionalities.
- **models/**: Directory containing the trained LSTM models.
- **data/**: Directory for storing training and testing datasets.
- **utils/**: Utility scripts for data preprocessing, model evaluation, and other helper functions.
- **requirements.txt**: List of required packages and dependencies for the project.
- **README.md**: This README file.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/stopthinkin99/gymbot.git
    cd gymbot
    ```
2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Ensure your webcam is connected and working.
2. Run the Jupyter Notebook:
    ```bash
    jupyter notebook gymrefinedmodel.ipynb
    ```
3. Follow the instructions in the notebook to start capturing video and receiving feedback.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to create an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For any questions or inquiries, please contact Aayan Boradia at aboradia@umass.edu.
