# decay_cavity_detection
# Caries Detection with YOLO and Streamlit

## Description

This project aims to detect dental caries in tooth images using the YOLO (You Only Look Once) object detection model. The system is trained to classify teeth into three categories: decay cavity, healthy tooth, and early decay.

## Features

- YOLO-based object detection for dental caries.
- Classification into three classes: decay cavity, healthy tooth, and early decay.
- Streamlit application for easy and interactive use.

## Getting Started

### Prerequisites

- Python 3.x
- Virtual environment (optional but recommended)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/caries-detection.git
    cd caries-detection
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Linux/Mac
    .\venv\Scripts\activate    # On Windows
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Download the pre-trained YOLO weights (if not included in the repository):
    - [Link to YOLO weights]

### Usage

1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.
   
3. Upload a tooth image to the application and observe the caries detection results.

## Training

If you want to train the YOLO model with your own dataset, follow these steps:

1. Prepare your dataset in the YOLO format.
2. Configure YOLO parameters in the `config` directory.
3. Train the model:
    ```bash
    python train.py
    ```

## Contributing

Contributions are welcome. Feel free to open issues or submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- YOLO model: [Link to YOLO repository]
- Streamlit: [Link to Streamlit documentation]

