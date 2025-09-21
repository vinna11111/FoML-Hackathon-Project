
# Kaggle-Style ML Pipeline: FoML Hackathon Project  

This repository contains my end-to-end solution for the **FoML 2024 Hackathon**.  
The project is designed in the spirit of Kaggle competitions, where the objective is to train a model on `train.csv` and generate predictions on a hidden/private `test.csv` in the correct submission format.  

## 🚀 Project Overview  
- Built a **reproducible ML pipeline** for tabular data.  
- Designed to run in a **Kaggle-like environment**: training on `train.csv`, inferring on private `test.csv`, and saving predictions to `output.csv`.  
- Follows **clean CLI interface** with `argparse` for test and output paths.  
- Works on **CPU-only environments** without additional setup.  
