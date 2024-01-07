
# Caries Detection with YOLO and Streamlit

## Description

This project aims to detect dental caries in tooth images using the YOLO (You Only Look Once) object detection model. The system is trained to classify teeth into three categories: decay cavity, healthy tooth, and early decay.

## Features

- YOLO-based object detection for dental caries.
- Classification into three classes: decay cavity, healthy tooth, and early decay.
- Streamlit application for easy and interactive use.
## Dataset

The dataset used for training and testing can be found ([[https://app.roboflow.com/yomna-hupf9/tooth_carries_2/2](https://app.roboflow.com/yomna-hupf9/tooth_carries_2/2)]).

## Getting Started

### Prerequisites

- Python 3.x
- Virtual environment (optional but recommended)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yomna99/caries-detection.git
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

4. Download the pre-trained YOLO weights :
    -best.pt

### Usage

1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.
   
3. Upload a tooth image to the application and observe the caries detection results.

![im![Capture d'écran 2024-01-07 235443](https://github.com/yomna99/decay_cavity_detection/assets/114284730/6a1e2531-8a19-4f03-b46e-85033b53147e)
age](https://github.com/yomna99/decay_cavity_detection/assets/114284730/0c252403-7714-4a0b-b461-987a2e1dee10)
![image](https://github.com/yomna99/decay_cavity_detection/assets/114284730/2668d091-ad29-4a23-b403-d2069f92aef2)



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

