
## Overview
Automatic segmentation of the Intima-Media Complex (IMC) in carotid ultrasound images using a UNet-based deep learning pipeline.

The project aims to estimate Intima-Media Thickness (IMT), a key biomarker for cardiovascular risk assessment.

Developed for a university competition (MIP Contest)  
Supervised by Prof. Filippo Molinari and Prof. Kristen Mariko Meiburger  

Final ranking: 2nd place  

Academic Year 2025/2026 

---

## Data

Main file `The Wolves of Wall MIP`  include:
- `training_script-final.ipynb`  # Model training pipeline
- `testing_code.ipynb`          # Model evaluation
- `IMT_function.ipynb`          # IMT computation
- `final-checkpoints/`          # Saved models and parameters
  - `best_model.pth`            # Best trained model
  - `training_params.json`      # Training configuration

---

## Method

- Ultrasound image pre-processing (median filtering)  
- UNet-based segmentation (PyTorch)  
- Loss optimization (BCE + Dice)  
- Thresholding and post-processing  
- IMT estimation from segmentation masks  

---

## Key Results

- Accurate IMC segmentation  
- Mean Dice Score ≈ 0.77  
- Reliable IMT estimation  
- 2nd place in the MIP Contest  

---

## Notes

Project focused on biomedical image segmentation using deep learning techniques applied to ultrasound data.
