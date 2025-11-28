<!-- Badges -->
<p align="center">
  
  <!-- Python -->
  <img src="https://img.shields.io/badge/Python-3.10-blue" alt="Python">

  <!-- Flask -->
  <img src="https://img.shields.io/badge/Flask-Web%20Framework-black" alt="Flask">

  <!-- PyTorch -->
  <img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-red" alt="PyTorch">

  <!-- Model Size -->
  <img src="https://img.shields.io/badge/Model%20Size-216MB-orange" alt="Model Size">

  <!-- License -->
  <img src="https://img.shields.io/badge/License-MIT-green" alt="MIT License">

  <!-- Repo Stats -->
  <img src="https://img.shields.io/github/stars/DileepKumarMS/DeepTrace-Tracking-Manipulations-in-Digital-Videos?style=social" alt="Stars">
  <img src="https://img.shields.io/github/forks/DileepKumarMS/DeepTrace-Tracking-Manipulations-in-Digital-Videos?style=social" alt="Forks">


# DeepTrace: Tracking Manipulations in Digital Videos

DeepTrace is a deepfake video detection system that combines a **ResNeXt-50** convolutional backbone with an **LSTM** to analyse sequences of video frames and classify them as **REAL** or **FAKE**. It provides a **Flask-based web interface** where users can upload a video, choose how many frames to analyse, and see:

- Final prediction (REAL / FAKE)  
- Model confidence (%)  
- Sample frames from the video  
- Detected faces with **colored bounding boxes**  
  - 🟩 Green → REAL  
  - 🟥 Red → FAKE  

---

## 🔗 Download Trained Model Weights

The trained PyTorch model is large (~216 MB), so it is **not stored directly in this repo**.

➡️ Download it from Google Drive:  
[Download model weights](https://drive.google.com/file/d/1Lq1ZmdUp7uZFTp5SI-07GVz2SL7zaX1L/view?usp=sharing)

After downloading, place the file here:

```text
models/model_90_acc_60_frames_final_data.pt
