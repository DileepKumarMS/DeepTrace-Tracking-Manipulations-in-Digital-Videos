# DeepTrace: Tracking Manipulations in Digital Videos

DeepTrace is a deepfake video detection system that combines a **ResNeXt-50** convolutional backbone with an **LSTM** to analyse sequences of video frames and classify them as **REAL** or **FAKE**.  

It provides a **Flask-based web interface** where users can upload a video, choose how many frames to analyse, and see:

- Final prediction (REAL / FAKE)  
- Model confidence (%)  
- Sample frames from the video  
- Detected faces with **colored bounding boxes**  
  - 🟩 Green → REAL  
  - 🟥 Red → FAKE  

---

## 🔍 Demo (UI Screenshots)

The project includes some UI screenshots under `website_screenshots/`:

- `deepLanding.png` – Landing page
- `upload.png` – Video upload page
- `result.png` – Results with prediction and frames

You can embed them in GitHub like this (optional):

```markdown
![Landing Page](website_screenshots/deepLanding.png)
![Upload Page](website_screenshots/upload.png)
![Result Page](website_screenshots/result.png)
