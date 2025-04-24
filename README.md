![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# 🧠 CNN Animal Classifier

This project is part of the **IronHack Machine Learning Specialization** and focuses on building Convolutional Neural Network (CNN) models to classify animal images from the [Animals10 Kaggle dataset](https://www.kaggle.com/datasets/alessiocorrado99/animals10). The final solution incorporates both **custom CNN architectures** and **transfer learning**, with model evaluation based on accuracy, F1-score, and confusion matrices.

---

## Bootstrap

1. Download the dataset by running the 1st cell.
2. Install python-dotenv module.
3. Create .env file.
4. Link your newly downloaded folder path to a variable called : DATASET_URI

---

## 📁 Repository Structure

This repository contains multiple notebooks created during the exploration and development process. The **final report and conclusions** are based primarily on the following:

- `pre_processing.ipynb` – Dataset loading, image resizing, splitting, and augmentation setup.
- `M1_Joao.ipynb` – Initial custom CNN architecture experimentation.
- `final_notebook_JJ.ipynb` – Final custom CNN model, training process, evaluation.
- `transfer_model_MO.ipynb` – Transfer learning implementation and final model selection.

Other notebooks in the repo may include additional experiments, visualizations, or helper scripts.

---

## 🧪 Dataset

- **Source:** [Animals10 - Kaggle](https://www.kaggle.com/datasets/alessiocorrado99/animals10/data)
- **Classes:** Dog, Cat, Horse, Spider, Butterfly, Chicken, Sheep, Cow, Squirrel, Elephant
- **Image Count:** ~28,000 images (medium quality)

---

## 📊 Final Model

After testing multiple CNN configurations, the best results were achieved using a **transfer learning** approach, which significantly improved validation performance and training efficiency.

- Framework: TensorFlow / Keras
- Preprocessing: Resizing, normalization, augmentation (flip, rotation, zoom, contrast)
- Final Accuracy Custom Model: ~73%
- Final Accuracy Transfer Learning Model: ~91%
- Evaluation Metrics: Precision, Recall, F1-score, Confusion Matrix

---

## 📝 Key Insights

- Transfer learning provided superior accuracy with less training time.
- Class weighting helped balance the model’s learning across underrepresented classes.
- Confusion matrices and classification reports revealed common misclassifications (e.g., cat ↔ cow, dog ↔ sheep).
- Time constraints and external commitments were limiting factors.
- Gladio deployment was optional and not completed due to time constraints.

---

## 🤝 Teamwork

> _"Working together as a group was pure bliss. We learned a lot from each other’s work and supported one another throughout the process."_

---

## 🧠 Authors

- João [@JoaoPeseiro]
- JJ [@Jyok1m]
- MO [@mobenet]

---

## 📅 Project Date

April 2025 – IronHack Final CNN Project

---

## 📌 License

This project is for educational purposes only.
