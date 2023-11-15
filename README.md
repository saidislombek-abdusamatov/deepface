## DeepFace Facial Recognition

This repository contains code for real-time facial recognition using the DeepFace library. The code utilizes a pre-trained facial recognition model (Facenet512) and an SSD-based face detector for real-time face detection.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/saidislombek-abdusamatov/deepface.git
    cd deepface
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

### [Usage](deepface_infernce)

1. **Setup Database:**
   - Set the `db_path` variable to the path where your face database is stored.


### Customization

- **Model and Detector Configuration:**
  - You can change the `model_name` variable to use a different pre-trained facial recognition model (e.g., "VGG-Face", "OpenFace").
  - Modify `detector_backend` to switch between face detection backends (e.g., "ssd", "opencv").

- **Distance Metric:**
  - Change the `distance_metric` variable to use a different distance metric for face matching (e.g., "cosine", "euclidean", "euclidean_l2").

- **Threshold and Filtering:**
  - Adjust the `threshold` variable to control the face matching sensitivity.
  - Modify filtering conditions (e.g., face size threshold) based on your requirements.

### References
- DeepFace: https://github.com/serengil/deepface
