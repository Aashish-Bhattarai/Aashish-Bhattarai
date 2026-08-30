# Aashish Bhattarai

ML/AI engineer. MSc Data Science (Distinction), University of Greenwich.

My focus is making machine learning and LLM output reliable enough to act on in
production: evaluation that reflects deployment rather than the test split,
calibrated confidence, and deterministic verification around probabilistic
components.

**Public work**

- **[ecommerce-sales-analysis](https://github.com/Aashish-Bhattarai/ecommerce-sales-analysis)**
  — cohort retention on UCI Online Retail II (1.07M transactions). Repeat buyers
  are 77% of customers but 98% of revenue. Documents a double-counting trap
  standard cleaning misses.
- **[customer-churn-prediction](https://github.com/Aashish-Bhattarai/customer-churn-prediction)**
  — Telco churn, with the parts most write-ups skip: calibration before
  thresholding, and a threshold derived from retention economics.
- **[Crop-Disease-Detection-ResNet-CNN](https://github.com/Aashish-Bhattarai/Crop-Disease-Detection-ResNet-CNN)**
  — ResNet18 transfer learning on PlantVillage, served via FastAPI.

**Private**

- **FieldTrust** — an evaluation harness measuring classifier degradation under
  distribution shift: lab-to-field accuracy, calibration, selective prediction.
  It showed a crop-disease model's 98% lab accuracy falling to 5% on field
  photography, with no confidence threshold able to make it safe. Available on
  request.

Python, PyTorch, FastAPI, PostgreSQL, React.
