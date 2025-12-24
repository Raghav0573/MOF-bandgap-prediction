# MOF bandgap prediction
This repository is my solution to the A1 problem statement of the ML4Science workshop conducted at IIIT Hyderabad in 2025.
![Uploading Gemini_Generated_Image_titt84titt84titt.png…]()


Use the [Google Drive link](https://drive.google.com/drive/folders/10eYYGBNEln7u3WORuh410OSX1LQam3rf?usp=sharing) to download the model weight and training data. 
### Files and their usage
1. **inference.ipynb**: To run inference on your own data. Load the pretrained model weights (model.pt) and scaler.pkl files to predict the band gap energy levels in metal organic frameworks (MOFs) using an Auto-encoder architecture. The input data consists of .cif structure files and a .csv file with the required columns. 
2. **A1_Autoencoder.ipynb**: This notebook outlines the entire data pre-processing workflow and model architecture. To retrain the model, download the dataset (train_dataset.zip) from the Google Drive link given above. 
