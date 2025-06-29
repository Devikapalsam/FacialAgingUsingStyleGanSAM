# FacialAgingUsingStyleGanSAM

This project uses the SAM model to simulate facial aging from age 0 to 100, and visualizes changes using various analytical graphs.

---

## 🚀 Features

- 👶→👴 Generate aged face images (10 to 110 years)
- 📊 Timeline and pixel difference graphs
- 📈 Cosine similarity & wrinkle detection
- 👁️ Eye area & facial region analysis
- 📉 Confusion matrix using ResNet34 predictions

---

## 🔧 Setup

```bash
pip install torch torchvision pillow dlib opencv-python matplotlib scikit-learn seaborn
````

* Add:

  * `sam_ffhq_aging.pt` to `pretrained_models/`
  * `image6.jpg` to `notebooks/images/`
  * `shape_predictor_68_face_landmarks.dat` to project root

---

## 📁 Output Files

* `output_aging_result1.jpg` – Stitched aged images
* `timeline1.png` – Aging timeline
* `pixel_difference1.png` – Pixel difference vs age
* `aging_similarity_graph1.png` – Similarity vs age
* `confusion_matrix.png` – Age group prediction accuracy
* ... and more

---

## 📦 Applications

* AI in Healthcare
* Digital Forensics
* Age Progression Studies

