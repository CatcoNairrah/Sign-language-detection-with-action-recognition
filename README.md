# 🤟 Sign Language Action Recognition (Mediapipe + LSTM)

This project detects sign language gestures in real time using your webcam. 
It uses Mediapipe to extract hand and body keypoints and trains an LSTM model to recognize different sign actions.
This model can predict these 9 actions: "Hello", "Welcome", "thank you", "iloveyou", "sorry", "please", "yes", and "no"
---

## Important Notes

- You **must collect your own data** before training the model.
- The dataset folder (`MP_Data`) and trained model weights (`.h5` files) are **not included**.
- This project works best in a **Python 3.8** environment.
- By running the data collection script, you will know which gestures you need to record.

---

## Setup Instructions

### 1. Set up Python 3.8 environment

