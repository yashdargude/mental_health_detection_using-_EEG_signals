# Mental Health Detection using EEG Signals

## Overview
This project focuses on detecting mental health conditions using EEG (Electroencephalogram) signals. By analyzing the brainwave data from multiple subjects, we aim to classify mental health states, including stress, anxiety, and others, using machine learning and image processing techniques.

The dataset consists of EEG recordings from 35 patients engaged in an intensive verbal mathematical task for 120 seconds. This data is processed to extract features for mental state prediction.

## Features
- **EEG Data Processing**: Extracting and cleaning raw EEG signals.
- **Machine Learning Model**: Leveraging machine learning to predict mental health states based on EEG signals.
- **Image Processing**: Visual representation of EEG data for better feature extraction and classification.
  
## Dataset
- 35 patients performing an intensive verbal mathematical task.
- EEG recordings for 120 seconds.
- Data saved in CSV format with brainwave activity.

## Technologies Used
- **Python**: For data processing, feature extraction, and model training.
- **OpenCV & Scikit-learn**: For image processing and machine learning.
- **Matplotlib**: For data visualization.
- **Git**: Version control.

## How to Use
1. Clone this repository:
    ```bash
    git clone https://github.com/yashdargude/mental_health_detection_using-_EEG_signals.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the preprocessing script to prepare the EEG data:
    ```bash
    python preprocess_data.py
    ```
4. Train the model using:
    ```bash
    python train_model.py
    ```

## Future Work
- **Real-time Detection**: Integrating real-time mental health monitoring.
- **Expanded Dataset**: Increase dataset size for better generalization.
- **Deep Learning Models**: Incorporate deep learning for better accuracy.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions, feel free to contact:
- Yash Dargude - yashdargude567@gmail.com
